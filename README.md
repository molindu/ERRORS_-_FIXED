# ERRORS_-_FIXED
# 2023.11.10
# 01. 'ViewPropTypes will be removed from React Native, along with all ' + 'other PropTypes. We recommend that you migrate away from PropTypes ' + 'and switch to a type system like TypeScript. If you need to ' + 'continue using ViewPropTypes, migrate to the ' + "'deprecated-react-native-prop-types' package."
  * I installed patch-package and used it through the cmd \n as npx patch-package pakage-name;
  * you can see, it creates patch folder with package name

# 02. ERROR  Warning: Cannot update a component (`App`) while rendering a different component (`Unknown`). To locate the bad setState() call inside `Unknown`, follow the stack trace as described in https://reactjs.org/link/setstate-in-render
  * Check and use useEffects when use if()/ else and normal setState changes.  

# 03. props should need to place with simple letters as first letter
