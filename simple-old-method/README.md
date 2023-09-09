# redux

##Architecture
![image](https://github.com/vwakesahu/redux/assets/89719144/7f01a692-8797-425b-8de0-a82337df76eb)
//old method
##Steps
install react-redux and redux
1. Ui Component
2. then store: src/redux/store.js create store = createstore()(from redux)
3. in index.js imp {Provider} form react-redux, store, Wrap whole app in Provider then pass store = {store} in provider
4. In store.js create reducer function
   like this:
   const reducer = (state, action) => {
   //state is current state, action is action is user's action
    switch(action.type){
        case "":
        default:
    }
   }
5. then pass reducer funct to store
6. Navigate yourself where you find the onclick is need
7. import useDispatch there , const dis=usedispatch()
8. add onclick where you have action
9. (e) => dispatch({type: })
10. output from store: import useSelector
11. const var = useSelector(state => state)

17:29
