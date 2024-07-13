# Star Rating Component

## Overview

This project provides a star rating component that visually displays a rating from 0.1 to 5.0 with animated filled stars. The rating is represented using a series of stars that fill up proportionally based on the rating value. This component is designed to be both interactive and visually appealing.

## Features

- **Rating Range:** Accepts rating values from 0.1 to 5.0.
- **Animated Display:** The stars fill up with a smooth animation based on the rating value.
- **Flexible Integration:** Easily integrates into any webpage.

## Usage

1. **HTML Structure:**

   ```html
   <div class="rating">    
       <div class="rating__body">
           <div class="rating__active"></div>
           <div class="rating__active">
               <input type="radio" class="rating__item" value="1" name="rating">
               <input type="radio" class="rating__item" value="2" name="rating">
               <input type="radio" class="rating__item" value="3" name="rating">
               <input type="radio" class="rating__item" value="4" name="rating">
               <input type="radio" class="rating__item" value="5" name="rating">
           </div>
       </div>
       <div class="rating__value">5</div>
   </div>
