# boilerplate-react-functional-public


Creating your own site require a lot of work. And if your concepts are weak its a headache. You might just end up on a single component for weeks. So lets make a small site. To test our basics.We will be creating a clone of Myntra shirtpage.
Details

Use the data given in data.js file.

nav bar:-

The website should have a navigation section. Created using nav var.

The nav bar should have logo of your website enclosed around a div tag with class icon-holder.

The nav bar should have a search bar, which on Enter keyDown event will do a case insensitive search over name and description of products, If a product's name or description contains the text in the input tag then it should be rendered in the div tag with id product-tile-holder.

The nav bar should also contain a cart svg ( can be found in the src folder with name shopping-cart-solid.svg). It should be enclosed in div tag with class cart-holder

Number of product(simple number) in the cart should be shown in the nav bar. And should be enclosed in div with class name cart-list-length



Filters:-

All the following options should be redered in a div tag with heading filter-holder.

Provide option to choose either Male or Female. (use radio button). Should be part of the same radio group(should only be able to choose one). By default select Male. This section should have a heading Gender.

Provide options to only display white shirts. (use checkbox) along with the label with text White.

Provide options to only display Folded Sleeves shirts. (use checkbox) along with the label with text Folded Sleeves. By default no option should be selected. This section should have a heading Categories.



Sorting:-

Render a dropdown using select tag to display sorting options. Should be able to sort the clothes depending on when they entered the market(What's New), prices(Price low to high), discounts (Better Discount). By default the data is arranged by the date they entered the market. To sort by price use finalPrice value. To sort by discounts use discounts value of the product.

Enclose this section in div tag with class sort-holder.



Content:-

Should render all products in a div tag with class product-tile-holder.

Each product should be rendered in a div tag with class indiv-tile-holder.

For each prodcut render its image(first link in otherImages), brand(name), description, price(finalPrice), old price(strikePrice), discount.

Old price should be enclosed in stike tag.

Final price should have format Rs. 554.

Discount text should have format like 60% OFF. Its font color should be red.

Description should be in italics.

Image should have width 200px.



Product Modal:-

On click event on any indiv-tile-holder a modal should open up.

Modal's content should be enclosed in div with id product-modal.

When no product is selected then #product-modal should not be rendered(not to render is different from display:none) :)

This modal contains all the images given in otherImages value of data. js for each product.

Show render a close option with text ×. On click of this text the modal should close.

Modal should all the sizes available for the product. Enclose each size option in div tag with class size-option. The size could be in different formats. Render like < div class="size-option" > XXL< /div>. For the size section render a heading Size Char.

Modal should have all the other details like name, description, discount, price(both)

Should render a button to add the product to cart. If product is added after selecting the size then the cart should remember the size selection.

On hover over the size-option its fonts color should be white and background should be red.

When Add to Cart button is clicked it should update cart immediately along with the new product and updated cart-list-length.



Cart:-

Should pop up when . cart-holder is clicked

The cart modal should have id cart-modal-content

It should contain all the selected Product details(name, description, finalPrice, strikePrice, discount).

It should calculate the Total items in the cart and display them as Total Items 5

It should calculate the Total Original Price(sum of strikePrice) in the cart and display them as Total Original Price 999

It should calculate the Total Discount(sum of (strikePrice - finalPrice)) in the cart and display them as Total Discount 1125

It should calculate the Final Price(sum of finalPrice) in the cart and display them as Final Price 5778

Render a Buy button



Acceptance Criteris

Use of correct class and id.

Working code for combination of filters

Search bar functionality.

Working code for cart.
