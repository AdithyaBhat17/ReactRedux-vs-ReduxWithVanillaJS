## Redux-TODO Application
This is a TODO App built with redux along with react

## How to run ?

clone this repository - `git clone https://github.com/AdithyaBhat17/ReactRedux-vs-ReduxWithVanillaJS.git`  
open `index.html` and play around :)


### Redux

#### Add task

```
    store.dispatch({
        type:ADD_TODO,
        todo:{
            id:0,
            name:'Learn Redux',
            complete:false
        }
    })
```

#### Remove task
```
    store.dispatch({
        type: REMOVE_TODO,
        id: 1
    })
```

#### Mark a task as COMPLETE
```
    store.dispatch({
        type: TOGGLE_TODO,
        id: 0
    })
```

#### Add a long-term GOAL
```
    store.dispatch({
        type: ADD_GOAL,
        goal: {
        id: 1,
        name: 'Lose 20 pounds'
        }
    })
```

#### Remove a long-term GOAL
```
    store.dispatch({
        type: REMOVE_GOAL,
        id: 0
    })
```
