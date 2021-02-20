# cheat_sheet
Taking some note about programmation

##React Note

ReactDOM.render(componentToRender, targetNode)
to creat a component with a function, need to creat a function returning JSX or null.
==> return(<div>my component</div>)
the function name should start with a capital letter
we can creat a component with a javascript class
don't forget to add ==> 
constructor(props) {
    super(props);
  }
//This is used to say that the component is ready and allow us to use this key word
add the code inside render ==>
render(){
<div>my code</div>
}

To add component together, 
1)we need to return app tag <app></app> inside the render
2)put the component inside the app inside tag which will make custom tag.
exemple:
return (
 <App>
  <Navbar />
  <Dashboard />
  <Footer />
 </App>
)

setState => ask to refresh while click (if onClick)
on[Event] => properties (convention)
handel[Event] => methode (convention)



##Normal ==> In React 

class ==> className
css comment /*my comment*/ ==> {/*my comment*/}
onclick ==> onClick // need to use camelCase
<br> ==> <br /> //always close tag !
<div></div> ==> <div></div> || <div /> // new way to writte tag. Note that the <div /> can't contain anything

