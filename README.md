# jQuery Plugin IconSelectBox

# Objective
As a developer our objective is to make things easy. This jQuery plugin will help you to create custom select box with icon or images.

![final-output](./Screenshot.png)

# Pre-requirements
    - jQuery  

# How to use
# Step 1 : 
Create select element with a unique `id`.
If you want to add images as an icon to `option list` then add image url to `data-icon` attribute otherwise assign `font-awesome icon class` to `data-icon` like in given example:

```HTML
	<select id="example" name="currency">
	  <option value="btc" data-icon="btc.png"> Bitcoin (BTC) </option>
	  <option value="eth" data-icon="eth.png"> Ethereum (ETH) </option>
	  <option value="bch" data-icon="bch.png"> Bitcoin cash (BCH) </option>
	</select>
```

# Step 2: 
Initialize the plugin like below:

```JavaScript
	$( selector ).IconSelectBox( isImage );
    // isImage: boolean;
```

To add image `isImage` should be `true` and for icons it should be `false`;


Finally you can get the value from your created `select element`.
like if you create element `#select-action` then you can get value like this 

```JavaScript
    $('#select-action').val();
```

Nothing complicated.

# Support us
<a href="https://www.hostg.xyz/SH6KQ"><img src="Support us.png" alt="To support my free tutorials and source code you can consider your next hosting purchase with my affiliate link. It will not cost you anything extra but it will give me a small amount of commission"/></a>

# Contributor
[Satpal Bhardwaj](https://sbsharma.com/ionic/)

# Follow us
<a target="_blank" href="https://www.facebook.com/Sbsharma-2798360506847821"><img src="https://img.shields.io/badge/Facebook-1877F2?style=for-the-badge&logo=facebook&logoColor=white"></a>
<a target="_blank" href="https://twitter.com/Ss101Bhardwaj"><img src="https://img.shields.io/badge/Twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white"></a>
<a target="_blank" href="https://www.linkedin.com/in/satpal-bhardwaj-5a76b4134"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"></a>
<a target="_blank" href="https://codepen.io/sb_sharma"><img src="https://img.shields.io/badge/Codepen-000000?style=for-the-badge&logo=codepen&logoColor=white"></a>
