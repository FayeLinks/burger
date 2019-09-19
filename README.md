# burger

## Keep track of your delicious burger creations with this app! 


## Check it out on Heroku!: 
[Open Here](#herokuapp/ "Burger App")

## Code Example:

``` <div class="row">
  <div class="col-lg-6">
<h2>Order Up!</h2>
<ol>
  {{#each burgers}}
    {{#if eaten}}
      {{> burgers/burger-block eat=false}}
    {{/if}}
  {{/each}}
</ol>
  </div>

<div class="col-lg-5">

<h2>Burgers that you've eaten!</h2>

<ol>
  {{#each burgers}}
    {{#unless eaten}}
      {{> burgers/burger-block eat=true}}
    {{/unless}}
  {{/each}}
</ol>

</div>
```

## Built With:
*  HTML
* Javascript
* JQuery 
* CSS
* Bootstrap
* MySQL
* Node
* Express


## Future Development: 
> Add a seperate form with sides and beverages that can be added to each burger


## Authors: 
* Alison Kelly