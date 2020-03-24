# food-bunker
Food Inventory, Meal Scheduler

### Models
1. Consumable
  * Name
  * Category
  * Recipe
  * Packages = []
    * Image
    * Measure
      * Amount
      * Type
    * Servings

2. Recipe
  * Name
  * Consumables
    * ID
    * Amount
      * Measure
      * Quantity
  * Peripherals
  * Description
  * Products

3. Plan
  * Date/Time
  * Items = []
    * Consumable
      * ID
      * Amount
        * Measure
        * Quantity
    * Recipe
      * Count
        * Measure
        * Quantity

### User Stories
* Create a Consumable.
* Add/Delete *n* packages of a Consumable.
* Create/Update a Recipe.
* Perform a Recipe.
  * Remove Consumables from Inventory.
  * Add Products to inventory
  * Update upcoming Plans with Recipe.
* Create/Update a Plan.
* Delete a Plan.
* Perform a Plan.
  * Remove Consumables from inventory.
* View upcoming Plans.
* View upcoming Recipes.

### Wireframes
