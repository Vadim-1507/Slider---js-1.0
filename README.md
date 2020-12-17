# Slider---js-1.0

It`s my first slider on native JavaScript, using html and css. If you want, you can use it in your projects.

For using slider in projects you need have html structure:

	<div class="offer__slider">
			<!-- Header slider -->
		<div class="offer__slider-counter">
			<div class="offer__slider-prev">
				  <img src="*.svg" alt="prev">
			</div>
			<span id="current">03</span>
			  /
			<span id="total">04</span>
			<div class="offer__slider-next">
				  <img src="*.svg" alt="next">
			</div>
		</div>
			<!-- Body slider -->
		<div class="offer__slider-wrapper">
			<div class="slider__inner">
				<div class="offer__slide">
					<img src="i*.jpg" alt="...">
				</div>
				<div class="offer__slide">
					<img src="*.jpg" alt="...">
				</div>
				<div class="offer__slide">
					<img src="*.jpg" alt="...">
				</div>
				<div class="offer__slide">
					<img src="*.jpg" alt="...">
				</div>
			</div>
		</div>
	</div>
    
If you can, you can modern code and use another structure.
***
When the slider was developed using WebPack.

To avoid errors in the module, please use, for example: `import slider from './modules/slider'`.

And to call the slider correctly use next structure:

	slider({
			container: '.offer__slider',
			slide: '.offer__slide',
			prevArrow: '.offer__slider-prev',
			totalCounter: '#total',
			currentCounter: '#current',
			wrapper: '.offer__slider-wrapper',
			field:'.slider__inner',
			nextArrow: '.offer__slider-next',
		});
		
Not all properties are required, it all depends on your project! You can experiment with it. 
***
The repository has a file of standard styles for the slider. But they are not required, and can be changed.
***
[My example this slider](https://drive.google.com/file/d/1xmOSu8bQzOEWslP02Mig74OuKANLuI5n/view?usp=sharing)
