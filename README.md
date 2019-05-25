# hello-world

<aura:component>

<aura:attribute name="name" type="string"/>

Welocme to Github Mr, {!v.name}

</aura:component>

//controller 

doInit:function(component,event,helper){
//var msg=cmp.get("v.msg");
component.set("v.name","Vivek");

} 

