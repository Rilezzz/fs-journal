# MVC




Wednesday, June 21st


1. Create new path within router,
ex: 
  path: '#/cars",

2. Create new controller 
ex:
  CarsController
    export class CarsController
    constructor (){
      console.log('Cars works?')
    }

3. Create view in router:
ex:
  view: '<h1> Cars Page</h1>'

4. Create new href link for cars page in nav bar (index.hmtl)

5. Creating car template:
  container-fluid,
  row,
  col-10 m-auto,
  ..... Once html is created we need to make a view page.

6. Create view page "CarView.js"
  -Paste html car template into view page 
  -Link view page to the router within  -view: ''-

7. Create car model within a model js sheet
  export class Cars{

    constructor (data){
    NOTE*: generateID creates a unique ID to find items within appState.
      this.id = generateId()
      ***
      this.img = data.img
      this.year = data.year
      this.make = data.make
      this.model = data.model
      this.miles = data.miles
      this.price = data.price
      this.description = data.description
      this.coler = data.color
      ***
      this.listingDate = new Date()
    }
  }

8. Create car template within CarView.js

  get CardTemplate(){
    return`
    html from index.html for cars section.
    `
  }

9. Make cars array within AppState (No need to list date or ID auto generates for you.)
  cars[{
    make:
    model:
    year:
    etc.....
  }

]

10. Create function in CarsController to draw cars to the page.
  (Look at gregslist reference to see code.)







