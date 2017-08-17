# Website Performance Optimization portfolio project


## PageSpeed Score Implemented Steps:

	* Compressed and re-sized images
	* Changed Google Analytics script to async version
	* Removed Google Fonts.
	* Changed style.css to inline CSS
	* Moved JS script to end of body
## Getting Rid of Jank Implemented Steps:
    * Removed Repeating “QuerySelectorAll” from For Loop in main.js
    * Refactored ChangePizzaSizes function to fix Forced Synchronous Layout and reduce time to resize pizzas to less than 5ms.
    * Added will-change:transform to .mover to render with a consistent frame-rate at 60fps when scrolling

### Customization with Bootstrap
The portfolio was built on Twitter's [Bootstrap](http://getbootstrap.com) framework. All custom styles are in `dist/css/portfolio.css` in the portfolio repo.

* [Bootstrap's CSS Classes](http://getbootstrap.com/css/)
* [Bootstrap's Components](http://getbootstrap.com/components/)


View on my [GitHib PageHere](https://jessica-rocket.github.io/frontend-nanodegree-mobile-portfolio/)