# 100 Days of Progress

## Objective
A personal plan I have developed to hold myself accountable to key goals and objectives between the dates of January 18, 2021 - April 26, 2021. I have mapped out a GANTT board on [monday.com](monday.com) to outline this process.

#### Key goals and objectives
1. Hone my skills in JavaScript by building JavaScript-heavy projects. 
2. Have a deeper understanding of React JS through open source.
3. Gain employment by the end of the 100 days.
4. Focus on mental health by curating 100 days of mantras and positive affirmations, as well as practicing mindfulness meditation.
5. Focus on physical health by having a 100 day meal plan and 100 day active plan.

## Calendar
<details><summary>Week 1 Objectives</summary>

Monday, 01/18/20 - Sunday, 01/24/20
1. Morning mantra (see Gantt for details).
2. Complete e-commerce shopping cart from scratch, plan design for single page layout (landing page).
3. Assigned Coding Nexus task (React project).
4. Begin reading Front End Developer's Handbook (https://frontendmasters.com/books/front-end-handbook/2019/#1.1). Finish Chapter 1 by EOW.
5. Physical activity (see Gantt for details).
6. Write Medium article on the JS array helper.
</details>

![](https://scontent.fdpa1-1.fna.fbcdn.net/v/t1.0-9/137224667_1303583540019484_6345447721045545497_o.jpg?_nc_cat=109&ccb=2&_nc_sid=0debeb&_nc_ohc=H0wbjbu0HQMAX-p3IJy&_nc_ht=scontent.fdpa1-1.fna&oh=5f17cba7ff1013d9a2e21ef285fe7e36&oe=60260C10)

<details><summary>Week 2 Objectives</summary>

Monday, 01/25/20 - Sunday, 01/31/20
1. Morning mantra (see Gantt for details).
2. Complete section 3 of 50 days of JS & plan design for single page layout.
3. Assigned Coding Nexus task (React project) from Week 1 Objectives.
4. Front End Developer's Handbook (https://frontendmasters.com/books/front-end-handbook/2019/#1.1). Finish Chapter 2 by EOW.
5. Physical activity (see Gantt for details).
</details>

![](https://scontent.fdpa1-1.fna.fbcdn.net/v/t1.0-9/138294479_1304905026554002_7015728169850880422_n.jpg?_nc_cat=107&ccb=2&_nc_sid=0debeb&_nc_ohc=EC_rUoiUMmIAX_t5xvK&_nc_ht=scontent.fdpa1-1.fna&oh=ac24058b87f3c898306c7a4351d3e42b&oe=60278993)

<details><summary>Week 3 Objectives</summary>

1. Morning mantra (see Gantt for details).
2. Complete section 3 of 50 days of JS & plan design for single page layout.
3. Assigned Coding Nexus task (React project).
4. Front End Developer's Handbook (https://frontendmasters.com/books/front-end-handbook/2019/#1.1). Finish Chapter 3 by EOW.
5. Physical activity (see Gantt for details).
6. Write Medium article on the JS array helper.
</details>

![](https://scontent.fdpa1-1.fna.fbcdn.net/v/t1.0-9/138644498_1304905959887242_3514607475845503786_o.jpg?_nc_cat=110&ccb=2&_nc_sid=0debeb&_nc_ohc=_3LzOV_yxTIAX-ieD1d&_nc_ht=scontent.fdpa1-1.fna&oh=2440948a21c82b5f8d02983a8b207ec2&oe=6027B54E)

<details><summary>Week 4 Objectives</summary>

1. JavaScript
2. React
3. Application process
4. Mantra and meditation
5. Activity
</details>

<details><summary>Week 5 Objectives</summary>

1. JavaScript
2. React
3. Application process
4. Mantra and meditation
5. Activity
</details>

<details><summary>Week 6 Objectives</summary>

1. JavaScript
2. React
3. Application process
4. Mantra and meditation
5. Activity
</details>

<details><summary>Week 7 Objectives</summary>

1. JavaScript
2. React
3. Application process
4. Mantra and meditation
5. Activity
</details>

<details><summary>Week 8 Objectives</summary>

1. JavaScript
2. React
3. Application process
4. Mantra and meditation
5. Activity
</details>

<details><summary>Week 9 Objectives</summary>

1. JavaScript
2. React
3. Application process
4. Mantra and meditation
5. Activity
</details>

<details><summary>Week 10 Objectives</summary>

1. JavaScript
2. React
3. Application process
4. Mantra and meditation
5. Activity
</details>

<details><summary>Week 11 Objectives</summary>

1. JavaScript
2. React
3. Application process
4. Mantra and meditation
5. Activity
</details>

<details><summary>Week 12 Objectives</summary>

1. JavaScript
2. React
3. Application process
4. Mantra and meditation
5. Activity
</details>

<details><summary>Week 13 Objectives</summary>

1. JavaScript
2. React
3. Application process
4. Mantra and meditation
5. Activity
</details>

<details><summary>Week 14 Objectives</summary>

1. JavaScript
2. React
3. Application process
4. Mantra and meditation
5. Activity
</details>

## Lessons Learned

<details><summary>Week 1 Lessons Learned</summary>

Date: Jan 18, 2021<br>
What I did: Project up, installation, testing, & reading documentation. I decided to put more focus on carefully reading and understanding the documentation, then implementing what I understood. Today, I installed [Tailwind CSS](https://tailwindcss.com/docs/installation) with npm. Tailwind CSS is a utility-first CSS framework, which means that it provides low-level utility classes that let you build completely custom designs without ever leaving your HTML.

Tailwind automatically removes all unused CSS when building for production, which means your final CSS bundle is the smallest it could possibly be. In fact, most Tailwind projects ship less than 10KB of CSS to the client. Some things to keep in mind with Tailwind: issues with repeating classes which makes readability more difficult.

What went well: Most of the project set up was fairly straight forward. I was able to orgnanize basic project files into folders and get started on the navigation for the e-commerce site. I read several articles about the pros/cons of Tailwind.

What could be improved: I ran into a few hiccups with Tailwind. After installation, none of the preset Tailwind classes I added were initializing on the server. I brought in peers to take a look at the project set up and we were not able to come to a resolution today. We believe that my current version of node.js may have something to do with it.<br>
Moving forward, I will be saving links to the articles I read so I can reference them another time. I am also going to attempt to rubber duck my way through the project more.

<hr>

Date: Jan 19, 2021<br>
What I did: I partnered with a peer to track down the location of the error. Our earlier suspicions about node being outdated was inaccurate. Instead, we found that there was an issue with where the CSS script was pointing. I now have the script pointing to the public directory, instead of the src one. If anyone knows why this works, I am open to feedback. This is the updated script ```<link href="/public/css/tailwind.css" type="text/css" rel="stylesheet">```. Link to the project files are [here](https://github.com/dcc5235/Portfolio).

What went well: I decided to make the site a cosmetic e-commerce page where the landing page links users to the product page. I have completed half of the product page and solely used Tailwind to style all elements. I figured out how to change the background image url by editing theme.backgroundImage in the tailwind.config.js file, but this can also be done by injecting ```style``` directly into HTML. 

What could be improved: As a reminder, if you use ```display: flex``` and ```justify-between``` in Tailwind, make sure width is set to 100% by using class ```container```. Otherwise, your elements won't have "free space" left to move. I found some inspiration for landing page ideas [here]( https://business.tutsplus.com/articles/product-landing-page-examples--cms-32174#:~:text=5%20Top%20Product%20Landing%20Page%20Design%20Trends%20for,...%205%20Get%20Bold%20With%20Your%20Images.%20).

<hr>

Date: Jan 20, 2021<br>
What I did: I was able to hard code the product section of the site and start on the shopping basket. I will come back to dynamically code both of these in JavaScript. I started reading Chapter 1 of the [Front End Developer's Handbook](https://frontendmasters.com/books/front-end-handbook/2019/#2).

Notables from Chapter 1:
- Front-end development = client-side development

![](https://frontendmasters.com/books/front-end-handbook/2019/assets/images/what-is-front-end-dev.png)

What went well: I gained some inspiration from [Sephora's](https://www.sephora.com/search?keyword=eyeshadow%20palette) products section. I decided to use Tailwind's preset breakpoints for CSS grid-template-column to change how the layout looked on different screens. The products section is completely responsive. 

What could be improved: I wanted the shopping bag to be hidden on x-axis and appear on hover. I wasn't able to find out how to add Tailwind classes to my code to get this effect. So, I opted to use plain CSS for it to function.

```
// HTML/Tailwind Classes
<div id="img-container" class="relative overflow-hidden hover:opacity-50">
  <img src="/images/img5.jpg" alt="product sample" class="block w-full min-h-full transition duration-300 ease-in">
    <button class="absolute px-3 py-2 font-bold tracking-widest uppercase transition duration-300 ease-in transform translate-x-full bg-gray-100 border-none cursor-pointer hover:bg-yellow-500 bg-opacity-80 top-3/4 -right-0" data-id="1">
      <i class="fas fa-shopping-cart"></i>
      add to bag
    </button>
</div>
 ```
 
 ```
// CSS          
#img-container:hover button {
  transform: translateX(0);
}
```

<hr>

Date: Jan 21, 2021<br>
What I did: I hard coded the shopping bag using flex box.  

What went well: The HTML & CSS portion of the products page is complete. I will be working on the logic tomorrow. Once the logic is complete for the products page, I will move forward with a landing page.

<hr>

Date: Jan 22, 2021<br>
What I did:  I created a products.json file to hold information on the product data (company name, name of product, price, image). Then, set up a function to retrieve the products using async await & display them as an organized array of objects in the console.

What went well: I was able to write this explanation for this portion of the logic & why you are able to see the data in the console.
```
// Retrieves products from products.json file
class Products {
  // async function enables us to write promise based code as if it were synchronous, 
  // without blocking the execution thread; always returns a promise
  async getProducts() { // get method retrieves data from local server (products.json)
    // try statement tests a block of code for errors
    try {
      // await operator waits for a promise to return a value within the function block
      let result = await fetch('products.json');
      let data = await result.json();

      let products = data.items;
      // map() array helper executes a function for every array element and return a new array that doesn't mutate the original
      // specifically, take a list of items in products.json and display it through map(), rather than call these items individually
      products = products.map(item => {
        // destructuring to organize the data on return
        const { id } = item.sys;
        const { company, title, price } = item.fields;
        const image = item.fields.image.fields.file.url;
        return { id, company, title, price, image }
      })
      // returns a clean version of the products.json file
      return products
      // catch statement handles the error after (try) testing the block of code
    } catch (error) {
      console.log(error);
    }
  }
}

// Event Listeners

// DOMContentLoaded event fires when the initial HTML document has been completely loaded and parsed, 
// without waiting for stylesheets, images, and subframes to finish loading.
document.addEventListener("DOMContentLoaded", () => { // Once content loads in DOM, then run the following...

  // new operator creates a new object, inheriting products from the above Products class
  const products = new Products();

  // get all products and then, display data (products) in the console
  products.getProducts().then(products => console.log(products));
});
```
![](https://pbs.twimg.com/media/EsX8E2ZXYAAKCu4?format=jpg&name=medium)

What could be improved: I think I could practice rubber ducking my way through the code a bit more. I will make it a habit to do this every day that I am coding.


<hr>

Date: Jan 23, 2021<br>
What I did: I used the displayProducts method to retrieve the products array. The forEach() helper executes a loop over the products array & for each product, gets props from each object & places them in the ${} in the template literal. All of this allows the products to be displayed in the user interface after the displayProducts method has been called. 

```
// Display Products Client-Side
class Display {
  // displayProducts method  (actions performd on objects) retrieves array named products
  displayProducts(products) {
    let result = '';
    // forEach() method executes a provided function once for each array element
    // loops over product array & for each product, retrieves props from each object & places it in the ${} template string
    products.forEach(product => {
      result += `
      <article class="text-2xl text-center">
          <div id="img-container" class="relative overflow-hidden hover:opacity-50 h-4/5">
            <img src=${product.image} alt="product"
              class="container block w-full min-h-full transition duration-300 ease-in">
            <button
              class="absolute px-3 py-2 font-bold tracking-widest uppercase transition duration-300 ease-in transform translate-x-full bg-gray-100 border-none cursor-pointer hover:bg-yellow-500 bg-opacity-80 top-3/4 -right-0"
              data-id=${product.id}>
              <i class="fas fa-shopping-basket"></i>
              add to basket
            </button>
          </div>
          <h3 class="mt-4 text-base tracking-widest text-center uppercase">${product.company}</h3>
          <h3 class="text-base tracking-widest text-center normal-case">${product.title}</h3>
          <h4 class="mt-3 tracking-widest text-center text-bold">$${product.price}</h4>
        </article>
      `
    });
    // innerHTML: change the page's content without refreshing the page. This can make website feel quicker and more responsive to user input
    productsDiv.innerHTML = result;
  }
}

// Event Listeners

document.addEventListener("DOMContentLoaded", () => { // Once content loads in DOM, then run the following...
  const display = new Display();
  const products = new Products();
  // get all products and then, display data (products) in the user interface
  products.getProducts().then(products => display.displayProducts(products));
});
```

What went well: The products displayed from the client side, it was responsive, and the products' image height were all the same value.

<img src="https://pbs.twimg.com/media/EscdY-eXEAYFi4M?format=jpg&name=medium" width="75%">

What could be improved: I converted the integers in the products.json file to strings, because the product price was excluding zeros at the end of each price (i.e. 8.50 => 8.5) otherwise. Does anyone know another way of converting integers to strings solely in the JS file? 
</details>
