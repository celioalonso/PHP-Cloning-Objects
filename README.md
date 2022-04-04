PHP Cloning Objects
PHP Program to criate copy of an object

Código pra se fazer a clonagem de um objeto utilizando PHP:

An object copy is created by using the clone keyword (which calls the object’s __clone() method if possible). An object’s __clone() method cannot be called directly. When an object is cloned, PHP will perform a shallow copy of all of the object’s properties. Any properties that are references to other variables will remain references.
