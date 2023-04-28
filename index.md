---
layout: default
---

<section class="bg-gray-100 py-10">
  <div class="container mx-auto px-4">
    <h2 class="text-3xl font-bold text-gray-900 mb-8">About ImCalculator</h2>
    <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-8">
      <div class="bg-white rounded-lg shadow-md">
        <img src="https://via.placeholder.com/350x200.png" alt="Placeholder Image" class="w-full h-48 object-cover rounded-t-lg">
        <div class="p-6">
          <h3 class="text-xl font-bold text-gray-900 mb-2">Why ImCalculator?</h3>
          <p class="text-gray-700 leading-6">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Mauris sit amet arcu eget quam auctor elementum a nec ipsum. Donec congue sapien id aliquam interdum.</p>
        </div>
      </div>
      <div class="bg-white rounded-lg shadow-md">
        <img src="https://via.placeholder.com/350x200.png" alt="Placeholder Image" class="w-full h-48 object-cover rounded-t-lg">
        <div class="p-6">
          <h3 class="text-xl font-bold text-gray-900 mb-2">Intuitive and User-Friendly</h3>
          <p class="text-gray-700 leading-6">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Mauris sit amet arcu eget quam auctor elementum a nec ipsum. Donec congue sapien id aliquam interdum.</p>
        </div>
      </div>
      <div class="bg-white rounded-lg shadow-md">
        <img src="https://via.placeholder.com/350x200.png" alt="Placeholder Image" class="w-full h-48 object-cover rounded-t-lg">
        <div class="p-6">
          <h3 class="text-xl font-bold text-gray-900 mb-2">Ad-Optimized</h3>
          <p class="text-gray-700 leading-6">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Mauris sit amet arcu eget quam auctor elementum a nec ipsum. Donec congue sapien id aliquam interdum.</p>
        </div>
      </div>
      <div class="bg-white rounded-lg shadow-md">
        <div class="aspect-w-16 aspect-h-9">
          <iframe src="https://www.youtube.com/embed/dQw4w9WgXcQ" title="Dummy Video" class="w-full h-full object-cover rounded-t-lg" frameborder="0" allowfullscreen></iframe>
        </div>
        <div class="p-6">
          <h3 class="text-xl font-bold text-gray-900 mb-2">ImCalculator Demo</h3>
          <p class="text-gray-700 leading-6">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Mauris sit amet arcu eget quam auctor elementum a nec ipsum. Donec congue sapien id aliquam interdum.</p>
        </div>
      </div>
    </div>
  </div>
</section>


<section class="bg-gray-100 py-16">
  <div class="container mx-auto">
    <h2 class="text-4xl font-bold text-center mb-12">About ImCalculator 🎲</h2>
    <div class="grid grid-cols-1 md:grid-cols-2 gap-8">
      <div>
        <h3 class="text-2xl font-bold mb-4">Clean and Intuitive</h3>
        <p class="text-gray-700 mb-6">ImCalculator provides a modern and user-friendly calculator tool ⚒️ that is easy to use and understand. The interface is designed to be clean and intuitive, allowing users to perform calculations quickly and efficiently.</p>
        <h3 class="text-2xl font-bold mb-4">Ad-Optimized 🪧</h3>
        <p class="text-gray-700 mb-6">Our ads are placed and optimized to avoid any impact on user experience 🤳, ensuring that you can use our tool without any distractions or interruptions.</p>
      </div>
      <div>
        <h3 class="text-2xl font-bold mb-4">Why We Created ImCalculator</h3>
        <p class="text-gray-700 mb-6">At ImCalculator, our aim is to provide a simple and easy-to-use calculator tool that helps people in their daily lives. We created ImCalculator to solve a common problem: the need for a reliable and user-friendly calculator that anyone can use.</p>
        <h3 class="text-2xl font-bold mb-4">How We Created ImCalculator</h3>
        <p class="text-gray-700 mb-6">We used the latest technologies and design principles to create ImCalculator, including modern frameworks like Daisy UI and Tailwind CSS. Our development process was focused on creating a tool that is both functional and aesthetically pleasing, ensuring that users have a great experience every time they use ImCalculator.</p>
      </div>
    </div>
  </div>
</section>



Text can be **bold**, _italic_, or ~~strikethrough~~.


[Link to another page](./another-page.html).

There should be whitespace between paragraphs.

There should be whitespace between paragraphs. We recommend including a README, or a file with information about your project.

# Header 1

{% include Calculators.html emoji="🔺🤑" Name="Hike Calculator" Description="Calculate hike" link="./another-page.html" %}

This is a normal paragraph following a header. GitHub is a code hosting platform for version control and collaboration. It lets you and others work together on projects from anywhere.

## Header 2

<div class="grid grid-cols-1 sm:grid-cols-2 md:grid-cols-3 lg:grid-cols-5 gap-6">
  <div class="card w-80 bg-base-100 shadow-xl">
    <div class="card-body">
      <div class="flex items-center justify-center h-16 w-16 rounded-full bg-gray-100">
        <span class="text-gray-400 text-4xl">💰</span>
      </div>
      <h2 class="card-title mt-4 text-lg font-medium text-gray-900">Calculator 1</h2>
      <p class="card-text mt-2 text-gray-600">Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
      <div class="card-actions justify-end">
        <a href="#" class="btn btn-primary mt-4">Calculate</a>
      </div>
    </div>
  </div>
  <div class="card w-80 bg-base-100 shadow-xl">
    <div class="card-body">
      <div class="flex items-center justify-center h-16 w-16 rounded-full bg-gray-100">
        <span class="text-gray-400 text-4xl">🧮</span>
      </div>
      <h2 class="card-title mt-4 text-lg font-medium text-gray-900">Calculator 2</h2>
      <p class="card-text mt-2 text-gray-600">Sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</p>
      <div class="card-actions justify-end">
        <a href="#" class="btn btn-primary mt-4">Calculate</a>
      </div>
    </div>
  </div>
</div>
  <div class="card w-80 bg-base-100 shadow-xl">
    <div class="card-body">
      {% include Calculators.html emoji="🔺🤑" Name="Hike Calculator" Description="Calculate hike" link="./another-page.html" %}
    </div>
  </div>
</div>


> This is a blockquote following a header.
>
> When something is important enough, you do it even if the odds are not in your favor.

### Header 3

```js
// Javascript code with syntax highlighting.
var fun = function lang(l) {
  dateformat.i18n = require('./lang/' + l)
  return true;
}
```

```ruby
# Ruby code with syntax highlighting
GitHubPages::Dependencies.gems.each do |gem, version|
  s.add_dependency(gem, "= #{version}")
end
```


<div class="flex justify-center my-10">
  <div class="step rounded-xl">
    <a href="#step1" class="step-content">
      <div class="step-title">Step 1</div>
      <div class="step-description">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Fusce bibendum enim eu commodo bibendum.</div>
    </a>
  </div>
  <div class="step rounded-xl ml-5">
    <a href="#step2" class="step-content">
      <div class="step-title">Step 2</div>
      <div class="step-description">Maecenas sed turpis at odio gravida rutrum non a massa. Sed a velit ac nisi aliquam dignissim.</div>
    </a>
  </div>
</div>

<div id="step1" class="flex justify-center my-10">
  <div class="step rounded-xl">
    <div class="step-title">Step 1</div>
    <div class="step-description">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Fusce bibendum enim eu commodo bibendum.</div>
  </div>
</div>

<div id="step2" class="flex justify-center my-10">
  <div class="step rounded-xl">
    <div class="step-title">Step 2</div>
    <div class="step-description">Maecenas sed turpis at odio gravida rutrum non a massa. Sed a velit ac nisi aliquam dignissim.</div>
  </div>
</div>




<div class="container mx-auto py-8">
  <div class="grid gap-4 md:grid-cols-3 lg:grid-cols-4">
    <div class="card w-80 bg-base-100 shadow-xl">
      <div class="card-body">
        <div class="flex items-center justify-center h-16 w-16 rounded-full bg-gray-100">
          <span class="text-gray-400 text-4xl">💰</span>
        </div>
        <h2 class="card-title mt-4 text-lg font-medium text-gray-900">Calculator 1</h2>
        <p class="card-text mt-2 text-gray-600">Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
        <div class="card-actions justify-end">
          <a href="#" class="btn btn-primary mt-4">Calculate</a>
        </div>
      </div>
    </div>

 <div class="card w-80 bg-base-100 shadow-xl">
      <div class="card-body">
        <div class="flex items-center justify-center h-16 w-16 rounded-full bg-gray-100">
          <span class="text-gray-400 text-4xl">📈</span>
        </div>
        <h2 class="card-title mt-4 text-lg font-medium text-gray-900">Calculator 2</h2>
        <p class="card-text mt-2 text-gray-600">Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
        <div class="card-actions justify-end">
          <a href="#" class="btn btn-primary mt-4">Calculate</a>
        </div>
      </div>
    </div>

 <div class="card w-80 bg-base-100 shadow-xl">
      <div class="card-body">
        <div class="flex items-center justify-center h-16 w-16 rounded-full bg-gray-100">
          <span class="text-gray-400 text-4xl">💳</span>
        </div>
        <h2 class="card-title mt-4 text-lg font-medium text-gray-900">Calculator 3</h2>
        <p class="card-text mt-2 text-gray-600">Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
        <div class="card-actions justify-end">
          <a href="#" class="btn btn-primary mt-4">Calculate</a>
        </div>
      </div>
    </div>

<div class="card w-80 bg-base-100 shadow-xl">
      <div class="card-body">
        <div class="flex items-center justify-center h-16 w-16 rounded-full bg-gray-100">
          <span class="text-gray-400 text-4xl">🏦</span>
        </div>
        <h2 class="card-title mt-4 text-lg font-medium text-gray-900">Calculator 4</h2>
        <p class="card-text mt-2 text-gray-600">Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
        <div class="card-actions justify-end">
          <a href="#" class="btn btn-primary mt-4">Calculate</a>
        </div>
      </div>
    </div>
  </div>
</div>


#### Header 4

*   This is an unordered list following a header.
*   This is an unordered list following a header.
*   This is an unordered list following a header.

##### Header 5

1.  This is an ordered list following a header.
2.  This is an ordered list following a header.
3.  This is an ordered list following a header.

###### Header 6


| head1        | head two          | three |
|:-------------|:------------------|:------|
| ok           | good swedish fish | nice  |
| out of stock | good and plenty   | nice  |
| ok           | good `oreos`      | hmm   |
| ok           | good `zoute` drop | yumm  |

### There's a horizontal rule below this.

* * *

### Here is an unordered list:

*   Item foo
*   Item bar
*   Item baz
*   Item zip

### And an ordered list:

1.  Item one
1.  Item two
1.  Item three
1.  Item four

### And a nested list:

- level 1 item
  - level 2 item
  - level 2 item
    - level 3 item
    - level 3 item
- level 1 item
  - level 2 item
  - level 2 item
  - level 2 item
- level 1 item
  - level 2 item
  - level 2 item
- level 1 item

### Small image

![Octocat](https://github.githubassets.com/images/icons/emoji/octocat.png)

### Large image

![Branching](https://guides.github.com/activities/hello-world/branching.png)


### Definition lists can be used with HTML syntax.

<dl>
<dt>Name</dt>
<dd>Godzilla</dd>
<dt>Born</dt>
<dd>1952</dd>
<dt>Birthplace</dt>
<dd>Japan</dd>
<dt>Color</dt>
<dd>Green</dd>
</dl>

```
Long, single-line code blocks should not wrap. They should horizontally scroll if they are too long. This line should be long enough to demonstrate this.
```

```
The final element.
```

<ul class="steps">
  <li class="step step-primary">Register</li>
  <li class="step step-primary">Choose plan</li>
  <li class="step">Purchase</li>
  <li class="step">Receive Product</li>
</ul>

<div class="bg-white py-10 px-4">
  <div class="max-w-screen-lg mx-auto grid gap-6 md:grid-cols-3 lg:grid-cols-4">
    <div class="bg-gray-100 rounded-lg shadow-md p-6">
      <div class="flex items-center justify-between mb-4">
        <h3 class="text-lg font-bold text-gray-800">Card 1</h3>
        <span class="text-gray-400 text-sm">4/10/2022</span>
      </div>
      <p class="text-gray-600">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</p>
      <a href="#" class="text-blue-500 hover:underline mt-4 block">Read more</a>
    </div>
    <div class="bg-gray-100 rounded-lg shadow-md p-6">
      <div class="flex items-center justify-between mb-4">
        <h3 class="text-lg font-bold text-gray-800">Card 2</h3>
        <span class="text-gray-400 text-sm">4/11/2022</span>
      </div>
      <p class="text-gray-600">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</p>
      <a href="#" class="text-blue-500 hover:underline mt-4 block">Read more</a>
    </div>
    <div class="bg-gray-100 rounded-lg shadow-md p-6">
      <div class="flex items-center justify-between mb-4">
        <h3 class="text-lg font-bold text-gray-800">Card 3</h3>
        <span class="text-gray-400 text-sm">4/12/2022</span>
      </div>
      <p class="text-gray-600">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</p>
      <a href="#" class="text-blue-500 hover:underline mt-4 block">Read more</a>
    </div>
    <div class="bg-gray-100 rounded-lg shadow-md p-6">
      <div class="flex items-center justify-between mb-4">
        <h3 class="text-lg font-bold text-gray-800">Card 4</h3>
        <span class="text-gray-400 text-sm">4/13/2022</span>
      </div>
      <p class="text-gray-600">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</p>
      <a href="#" class="text-blue-500 hover:underline mt-4 block">Read more</a>
    </div>
  </div>
</div>
