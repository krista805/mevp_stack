PROXY allows one object to control properties and methods of another one. This can bring great convenience to us. For example, PROXY allows data to travel freely between properties in Vue instance. 

- Property and method cannot be used alone, they must be prefixed with their object name.

- New ES6 concept

- Proxy allows us to control properties of the data object (data: {message:"Message Property"}) from the vm object (ie. var vm)

- Proxy also works on methods, meaning you can proxy a method. See example of alert that was created in index.html

- Methods and computed can directly access properties using the keyword "this"


- You vue program will consist of:
    - el
    - data: is for storing data
    - computed: is for processing data
    - methods: is for processing data