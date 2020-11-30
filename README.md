hello, World
function greeting(name = null) {
	if(name) {
		return "Hello " + name
	} else {
		return "Howdy friend!"
	}
}
console.log(greeting("Andres"))
console.log(greeting())