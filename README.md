# Bind Action Creators
redux studies

***Turns an object whose values are action creators, into an object with the same keys, but with every action creator wrapped into a dispatch call so they may be invoked directly.***

## Clone the repo & install
```
git clone https://github.com/suxxuscomp/bind-action-creators.git
cd ./bind-action-creators.git
npm install
```
## Usage
cd ./src/scripts

**node index.js**

## Tips
* The only use case for bindActionCreators is when you want to pass some action creators down to a component that isn’t aware of Redux

## Links
[bindActionCreators](http://redux.js.org/docs/api/bindActionCreators.html)
