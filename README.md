# I know that some stuff are hidden, I will fix it later  


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

setState => ask to refresh while click (if onClick) important to use this methode to update. Never use state
on[Event] => properties (convention)  
handel[Event] => methode (convention)  

.bind(this) => used on the event to set the this. Without that, the this is undefined because it's inside an event. Exemple: "<button onClick={this.handelClick.bind(this)}>Click me</button>"
or  
<button onClick={()=>this.handelClick()}>Click me</button>" => use function to keep the 'this'  
or  
make handelClick a function


##Normal ==> In React 

class ==> className
css comment /*my comment*/ ==> {/*my comment*/}
onclick ==> onClick // need to use camelCase
<br> ==> <br /> //always close tag !
<div></div> ==> <div></div> || <div /> // new way to writte tag. Note that the <div /> can't contain anything

