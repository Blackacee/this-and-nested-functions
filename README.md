# this-and-nested-functions
 
document.getElementById('myAJAXButton').onclick = function(){
 var self = this;
 makeAJAXRequest(function(result){
 if (result) { // success
 self.className = 'success';
 }
 })
}
