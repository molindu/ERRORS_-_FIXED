# ERRORS_-_FIXED
# 2023.11.10
# 01. 'ViewPropTypes will be removed from React Native, along with all ' + 'other PropTypes. We recommend that you migrate away from PropTypes ' + 'and switch to a type system like TypeScript. If you need to ' + 'continue using ViewPropTypes, migrate to the ' + "'deprecated-react-native-prop-types' package."
  * I installed patch-package and used it through the cmd as npx patch-package pakage-name;
  * you can see, it creates patch folder with package name

# 02. ERROR  Warning: Cannot update a component (`App`) while rendering a different component (`Unknown`). To locate the bad setState() call inside `Unknown`, follow the stack trace as described in https://reactjs.org/link/setstate-in-render
  * Check and use useEffects when use if()/ else and normal setState changes.  

# 03. props should need to place with simple letters as first letter

# 04. When error comes while pushing 
"Total 96 (delta 61), reused 0 (delta 0), pack-reused 0
error: RPC failed; curl 56 HTTP/2 stream 7 was reset
send-pack: unexpected disconnect while reading sideband packet
fatal: the remote end hung up unexpectedly"
# to do 
* git config --global http.version HTTP/1.1, push, then git config --global http.version HTTP/2
# Follow this 
link - https://github.com/curl/curl/issues/11353#issuecomment-1687169241
# 2023.11.18
# Error: [Reanimated] `valueUnpacker` is not a worklet, js engine: hermes
 module.exports = {
  presets: ['module:metro-react-native-babel-preset'],
  plugins: ['react-native-reanimated/plugin'],
}; 
* link - https://github.com/georstat/react-native-image-cache/issues/67#issuecomment-1785035304
