
# T7 AI Powered Content Generator

  

T7 AI Powered Content Generator is a Web App that generates content specifically tailored to the Torpedo7 Brand for use in Torpedo7's website, social media and for SEO. <br><br>To see it in action [click here](https://t7contentgenerator.netlify.app/). <br><br>
This web app aims to make generating content using Chat-GPT for T7 easy and efficient by simplifying user prompts to provide much more consistent and effective results without having to go through a tonne of prompt engineering and or testing.<br><br>

## Known Issues
<strong>NOTE </strong>- There is currently a known issue/ bug where the error handling notification does not display when request has failed. If your response has failed to output for more than 30 seconds please wait a minute or so and refresh the application. If this does not fix the issue please note it is likely that the Server is currently experiencing issues and you may have to try again after a longer period of time.
<br>
<br>

## Usage Guide
To use the web app - simply select the option you would like to use/ generate - input the appropriate data (Expected data can be found in each dropdown below) into the user input box and click generate.

<br>

<details>
  <summary>SEO Web Blurb Generator:</summary>
  <br>

- Generates an SEO friendly blurb for use in webpages on the website - produces content that is less likely to be AI detectable. The output is atleast 120 words and upto at most 300 words. 

  <br> 
  
##### Sample Input Data: 
<i>Expected Input: Topic</i>
  
- Black Friday<br>
- Camping<br>
- Gifts for Mother's Day

  </details><br>
  
  
<details>
  <summary>Product Content Generator</summary>
<br>

- Generates an product description blurb for use in product description pages on the website - produces content that is less AI detectable. The output is atleast 350 characters long.
<br>
  
##### Sample Input Data: 
  <i>Expected Input: Product Name in Double Quotes and Features/ Benefits listed below</i>

- "Torpedo7  Compact HD Chair - Black/Grey"<br>
Mesh drink holder<br>-Lightweight, compact design<br>
Carry bag included<br>
Fabric: 600D Polyester<br>
Frame construction: 16mm Powder Coated Steel<br>
Dimensions: 52 x 42 x 41/78cm<br>
Packed dimensions: 83 x 15cm<br>
Weight: 2.4kg<br>
Max Load: 100kg<br>

  </details><br>

<details>
  <summary>Social Content Generator</summary>
<br>

- Generates a blurb for use in social media - produces content that is less AI detectable. The output is atleast 100 characters and upto 150 characters long.
<br>
  
##### Sample Input Data: 
<i>Expected Input: Topic or Topic and Product</i>

- Back to School with the Hydroflask lunch box<br>
- Start of Summer Season<br>
- Winter Essentials<br>

  </details><br>

<details>
  <summary>EDM Subject Line Generator</summary>
<br>

- Generates a subject line for EDMs - produces suggestions. Output will have minimum of 9 characters upto a total of 60 characters.
<br> 
  
##### Sample Input Data: 
<i>Expected Input: Topic</i>

- Camping over Waitangi Weekend<br>
- Easter Sale<br>
- Black Friday sale with 30% off everything<br>

  </details><br>

<details>
  <summary>SEO Technical Keyword Generator</summary>
<br>

- Generates related technical keywords/ terms for copy - generates technical terms related to input topic that can be leveraged in content to appeal to audience. Pulls the top 15 most common technical terms related to input topic.
<br> 
  
##### Sample Input Data: 
<i>Expected Input: Topic</i>

- Biking<br>
- Horse Riding<br>
- Clothing<br>

  </details><br>

<details>
  <summary>SEO Longtail Generator</summary>
<br>
  
- Generates related longtail keywords - generates long-tail queries related to the input topic to help identify potential opportunities. Pulls the top 15 long tail queries.
<br>

##### Sample Input Data: 
<i>Expected Input: Topic</i>

- Snowboard<br>
- School<br>
- Clothing<br>

  </details><br>

  <details>

  <summary>SEO Ad Copy Generator</summary>
<br>
  
- Generates possible ad copy headlines - generates ad copy headlines related to the input topic. The output will be upto 90 characters including spaces.
  <br>
  
  
##### Sample Input Data: 
<i>Expected Input: Topic</i>

- Black Friday<br>
- Camping<br>
- Mammoth Bikes<br>

  </details><br>

<details>
  <summary>Content & Copy Reviewer</summary>
<br>
  
- Reviews input topic in order to ascertain main tonalities of messaging/ input text and suggests potential improvements to improve copy.
  <br>
  
##### Sample Input Data: 
<i>Expected Input: Copy</i>

- With us you will find all the gear that you need for your next adventure in New Zealand or abroad. We also have buying guides to help you find the products that fit your needs and inspirational articles to guide you to the best outdoor spots in New Zealand. Our staff are passionate about our products and will gladly advise you on the best fit for your needs. We also offer repair and maintenance services for your snow and bike gear in several stores across New Zealand. Just wanting to try some things out? No worries, we also have bike and ski rental services available too!<br>

</details><br>
  
## WIP

Currently working on implementing sample data into Custom Models in order to generate more effective and accurate results (Fine tuning custom models via OpenAI API). 
<br><br>

## Credits

Special thanks to [@Tianrens](https://github.com/Tianrens) and [@parfei](https://github.com/parfei) for helping and advising the debugging, refactoring of the code in order for this personal project to come to life!

An additional thank you to the people who have helped me test and improve the user experience!

Lastly - big thank you for OpenAI for making their API accessible and easy to use so we can all leverage the power and potential of Chat-GPT!
