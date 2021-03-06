# Understanding the File Structure

- `/docs` - Github Repo Documentation
- `/firebase` - Firebase samples
- `/native-base-theme` - React Native's theme (by NativeBase)
- `/public` - Web server runs from here
- `/src` - Contains the source code for both web & native
    - `/actions` - Redux Actions - payloads of information that send data _from_ your application _to_ your store. [Read More &rarr;](https://redux.js.org/docs/basics/Actions.html)
    - `/constants` - Shared variables (across platforms)
    - `/containers` - 'Smart-components' that connect business logic to presentation [Read More &rarr;](https://redux.js.org/docs/basics/UsageWithReact.html#presentational-and-container-components)
    - `/images` - Images shared across platforms
    - `/lib` - Utils and custom libraries that are shared across platforms
    - `/native` - React Native specific code
        - `/components` - 'Dumb-components' / presentational. [Read More &rarr;](https://medium.com/@dan_abramov/smart-and-dumb-components-7ca2f9a7c7d0)
        - `/constants` - Native-specific variables and config
        - `/routes`- wire up the router with any & all screens [Read More &rarr;](https://github.com/aksonov/react-native-router-flux)
    - `/reducers`- Redux Reducers - Actions dispatch to reducers, which actually change the state [Read More &rarr;](https://redux.js.org/docs/basics/Reducers.html)
    - `/store`- Redux Store - hooks up the stores and provides initial/template states [Read More &rarr;](https://redux.js.org/docs/basics/Store.html)
    - `/web` - React-Web specific code
        - `/components` - 'Dumb-components' / presentational. [Read More &rarr;](https://medium.com/@dan_abramov/smart-and-dumb-components-7ca2f9a7c7d0)
        - `/routes`- wire up the router with any & all screens [Read More &rarr;](https://github.com/aksonov/react-native-router-flux)
        - `/styles`- all the SCSS you could dream of
