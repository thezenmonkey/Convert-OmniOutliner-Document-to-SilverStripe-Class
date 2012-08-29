# OmniOutliner to SilverStripe Classes
This script converts OmniOutliner files based on the [template](http://designplusawesome.com/assets/resources/SilverStripeClass.oo3template.zip).

I found I'd do my Database planning in OmniOUtliner and needed a quick way to convert that file to my SilverStripe classes

So far it builds just the basic class (db, has_one, has_many, many_many, etc).
 
Compile as an application then just drop your ooh file on to it and select a project folder, it'll handle the rest.
## How to use the Template File
Duplicate the Sample Class for each class you want to create
Name the class and define the Parent Class in the Extension Column

Under the db you need to select a type from the drop down column, if it's an Enum; list out the values in the EnumValues column

Under the relations you can define the related class Relation Column
## To Do
* Add CMSField build
* Add convert notes to standard docblock comments
* Add fields for more robust docblock descriptions 