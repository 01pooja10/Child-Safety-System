<p align="center">
<a href="https://dscommunity.in">
	<img src="https://github.com/Data-Science-Community-SRM/template/blob/master/Header.png?raw=true" width=80%/>
</a>
	<h2 align="center"> Online Child Safety</h2>
	<h4 align="center"> An application that detects and warns users against potential predators in online chatrooms <h4>
</p>

---
[![DOCS](https://img.shields.io/badge/Documentation-see%20docs-green?style=flat-square&logo=appveyor)](INSERT_LINK_FOR_DOCS_HERE)
  [![UI ](https://img.shields.io/badge/User%20Interface-Link%20to%20UI-orange?style=flat-square&logo=appveyor)](INSERT_UI_LINK_HERE)

## Preview of the application
The purpose of our application was to build a bot (called SAF in the images shown below) which warns users against potential predators while engaging in conversations via (online) chatrooms. It is based on predictions made by the LSTM model trained on dangerous and relatively normal conversations.

__Welcome Page__

![Welcome page](data/bot6.jpg)

__Potentially dangerous chats__

![dangerous chats](data/bot2.jpg)
![dangerous chats](data/bot3.jpg)

__Normal chats__

![normal chats](data/bot1.jpg)
![normal chats](data/bot5.jpg)

## Functionalities

- [ ]  Detects potential predators in online chatrooms.
- [ ]  Provides a chatting interface with the bot which generates responses and predicts whether they're dangerous or safe.
- [ ]  Displays warning messages when texts are perverted or suspicious.
- [ ]  User can also provide text inputs to the bot which will then detect how perverted they are.

<br>


## Instructions to run

* Dependencies:
	-  Tensorflow
	-  Keras
	-  Numpy
	-  Pandas
	-  pickle
	-  NLTK
	-  Symspellpy
  -  Streamlit

* The Bot (application) has been built using Streamlit.

## Future improvements

* Model's responses are random and can instead be tailored to fit user's responses or questions.
* The bot makes accurate predictions as to whether a conversation is dangerous or not, most of the time, but requires fine-tuning.
* Each conversation between the bot and user lasts only for one iteration. This can be extended to include actual conversations.
* This bot can be built as an extension instead of a stand-alone application and can be employed in actual online chatrooms.

## Contributors

<table>
<tr align="center">


<td>

Naman Garg

<p align="center">
<img src = "https://avatars.githubusercontent.com/u/40496687?s=400&u=aeba7754d8bba23a2ab9fb2d794cc316b2b6a84b&v=4"  height="120" alt="Naman Garg">
</p>
<p align="center">
<a href = "https://github.com/Namangarg110"><img src = "http://www.iconninja.com/files/241/825/211/round-collaboration-social-github-code-circle-network-icon.svg" width="36" height = "36"/></a>
<a href = "https://www.linkedin.com/in/naman-garg-3790b917a/">
<img src = "http://www.iconninja.com/files/863/607/751/network-linkedin-social-connection-circular-circle-media-icon.svg" width="36" height="36"/>
</a>
</p>
</td>


<td>

Pooja Ravi

<p align="center">
<img src = "https://avatars.githubusercontent.com/u/66198904?s=400&u=8b808b3dae9c8885445eadfa5e50ba260d9305f7&v=4"  height="120"
alt="Pooja Ravi">
</p>
<p align="center">
<a href = "https://github.com/01pooja10"><img src = "http://www.iconninja.com/files/241/825/211/round-collaboration-social-github-code-circle-network-icon.svg" width="36" height = "36"/></a>
<a href = "https://www.linkedin.com/in/pooja-ravi-9b88861b2/">
<img src = "http://www.iconninja.com/files/863/607/751/network-linkedin-social-connection-circular-circle-media-icon.svg" width="36" height="36"/>
</a>
</p>
</td>



<td>

Breenda Das

<p align="center">
<img src = "https://avatars.githubusercontent.com/u/66198218?s=400&u=626a6d7ce4f3ea271bd3f09c67a109c0eeb69f44&v=4"  height="120" alt="Breenda Das">
</p>
<p align="center">
<a href = "https://github.com/ds-brx"><img src = "http://www.iconninja.com/files/241/825/211/round-collaboration-social-github-code-circle-network-icon.svg" width="36" height = "36"/></a>
<a href = "https://www.linkedin.com/in/breenda-das-68a1891aa/">
<img src = "http://www.iconninja.com/files/863/607/751/network-linkedin-social-connection-circular-circle-media-icon.svg" width="36" height="36"/>
</a>
</p>
</td>

<td>

Sadhavi Thapa

<p align="center">
<img src = "https://avatars.githubusercontent.com/u/77241570?s=400&v=4"  height="120"
alt="Sadhavi Thapa">
</p>
<p align="center">
<a href = "https://github.com/Sadhavithapa"><img src = "http://www.iconninja.com/files/241/825/211/round-collaboration-social-github-code-circle-network-icon.svg" width="36" height = "36"/></a>
<a href = "https://www.linkedin.com/in/sadhavi-thapa-8b153b18b/">
<img src = "http://www.iconninja.com/files/863/607/751/network-linkedin-social-connection-circular-circle-media-icon.svg" width="36" height="36"/>
</a>
</p>
</td>
</tr>
  </table>

## License
[![License](http://img.shields.io/:license-mit-blue.svg?style=flat-square)](http://badges.mit-license.org)

<p align="center">
	Made with :heart: by <a href="https://dscommunity.in">DS Community SRM</a>
</p>
