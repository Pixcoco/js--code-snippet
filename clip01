<script> 
//对象写法一
var myDog = {
    "name" : "Spot",
    "bark" : function() { alert("Woof!"); },
    "displayFullName" : function() {
        alert(this.name + "The Alpha Dog");
    },
    "chaseMrPostman" : function() { 
        // implementation beyond the scope of this article 
    }    
};
myDog.displayFullName(); 
myDog.bark(); // Woof!

//对象写法二
function Demo(){
        console.log("test");
        Demo.testJs = function(){
          console.log(this); 
        console.log("testDemo");
        }
        
};
        
  var demoA = new Demo();
  demoA.testJs();
  

//静态方面定义一
var Play =(function(){
        console.log("testPlay");
        this.testJs = function(){
          console.log(this);  
        };
return this; //返回对象实例  
})();
Play.testJs();

//静态方法定义二
var Play =function(){
    console.log("testPlay");
    Play.testJs = function(){
    console.log(this);  
    };
  
};
Play();
Play.testJs();
//静态方法定义三
var Play =function(){
    console.log("testPlay");
};
Play.testJs = function(){
    console.log(this);  
};
Play.testJs();
</script>
