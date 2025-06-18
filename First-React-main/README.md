# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

## Expanding the ESLint configuration

If you are developing a production application, we recommend using TypeScript with type-aware lint rules enabled. Check out the [TS template](https://github.com/vitejs/vite/tree/main/packages/create-vite/template-react-ts) for information on how to integrate TypeScript and [`typescript-eslint`](https://typescript-eslint.io) in your project.


prevoiusly to create react application without any external framework we will use npx create-react-app to run npm start

but now stable version of react 19 was introduced 


react js is a frontend framework which you can use to build complex UI'S by the support of virtual DOM and JSX - you can seamlessly build UI components.

in Js - when you update any part of dom the entire dom is updated 

virtual DOM: it will update only one part or the part that needs to be updated , no entire updation 
the document has other part that will not be affected.

at final phase this virtual dom will create a copy and update the original dom

-Diffing algorithm 

JSX - javascript + XML it supports js  in html

export some file:
function Component(){
    //pure js you have to write
    return (
        // html + js - you can write
    )
}

export default Component;

Fragments: writing under one tag
<>
//.......
</>


to write class : <div className="someName" ></div>