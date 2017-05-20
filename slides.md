# Refactoring Lengthy Bits of Code

## Maria Mckinley



## Step 1

Write out in prose (or say outloud) what is happening in the function/block of code that you want to refactor.

We are opening up a window, and setting its resolution, and then opening up a second window, and setting its resolution. Then we are setting other properties for the windows, lenses and cameras<!-- .element: class="fragment" data-fragment-index="1" -->

_Wait a minute, why are we doing it that way?_<!-- .element: class="fragment" data-fragment-index="2" -->




## Step 2

Make an outline. Yes, old-fashioned outline like your English teacher made you write before you could start your essay.

Sample Outline<!-- .element: class="fragment" data-fragment-index="1" -->

1. Open both Windows<!-- .element: class="fragment" data-fragment-index="1" -->
   * a. set resolution<!-- .element: class="fragment" data-fragment-index="1" -->
2. Set Properties<!-- .element: class="fragment" data-fragment-index="1" -->
   * a. window<!-- .element: class="fragment" data-fragment-index="1" -->
   * b. lens<!-- .element: class="fragment" data-fragment-index="1" -->
   * c. camera<!-- .element: class="fragment" data-fragment-index="1" -->



## Step 3 

_Notice that the outline may not make sense._<!-- .element: class="fragment" data-fragment-index="1" -->

_Play around with outline until it actually makes sense._<!-- .element: class="fragment" data-fragment-index="2" -->

_Subpoints may not be necessary to outline._<!-- .element: class="fragment" data-fragment-index="3" -->

Sample Outline 2<!-- .element: class="fragment" data-fragment-index="4" -->

1. Open both Windows<!-- .element: class="fragment" data-fragment-index="4" -->
2. Set Window properties<!-- .element: class="fragment" data-fragment-index="4" -->
3. Set Lens Properties<!-- .element: class="fragment" data-fragment-index="4" -->
4. Set Camera Properties<!-- .element: class="fragment" data-fragment-index="4" -->



## Step 4

Your main bullet points are your new function calls.

Everything else goes in one of these calls.



## Step 5

Write a test for each of your new functions!
