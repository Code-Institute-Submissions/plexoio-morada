# Morada NFT - Main Webpage

Morada NFT is a landing page for purchasing functional NFTs offered by a hotel. "Functional" in this context refers to NFTs that hold real value or utility. Apart from receiving special benefits, free stays, surprises, VIP services, and more, clients will be at the forefront of the most advanced technology available for membership management and ticket issuance. Users become part of the hotel by holding an NFT, which is 100% tradable and valid for lifetime use.

The static website is built on `HTML`, `CSS`, and subtle features using `Javascript`. It is fully responsive, structured, and organized.

As evident from all the information provided in this Readme.md, the state of this released product should be considered as an `MVP` for the main features.

Please note that this project is not available for public deployment; **it is intended solely for learning and demonstration purposes** even though is ready for use.

**Preview Link:** [Morada Hotel](https://plexoio.github.io/morada/index.htm)


## Index

1. <a href="#strategy">Strategy - Reason, Solution and Value</a>
2. <a href="#scope">Scope - Feature and Capability</a>
3. <a href="#structure">Structure - Content, Priority and Organization</a>
4. <a href="#skeleton">Skeleton - Layout, Interaction and relationship</a>
5. <a href="#surface">Surface - Color, Typography, Effect and Images</a>
6. <a href="#technologies">Technologies used</a>
7. <a href="#testing">Testing</a>
8. <a href="#development">Development process</a>
9. <a href="#deployment">Deployment</a>
10. <a href="#graphics">Graphic sources</a>
11. <a href="#credits">Credits</a>

## Badges

[![MIT License](https://img.shields.io/badge/License-MIT-green.svg)](https://choosealicense.com/licenses/mit/)


## Strategy
This leading hotel embraces innovative technology to differentiate from competitors, appealing to `clients` who value progressive advancements. Hotel membership is seen as a substantial investment for stakeholders and regular clients, comparable to an exclusive, generational club.

To securely preserve membership data, the hotel employs blockchain technology on the Polygon Network, reducing paperwork, costs, and environmental impact while efficiently verifying memberships.

Morada's balanced philosophy combines stoicism and hedonism for a well-rounded life experience. By adopting NFTs on the Polygon Network, the hotel effectively manages memberships, allows interoperability with partner services, and streamlines identity verification for `clients`.

The `Morada Platform` aims to present these variety of innovative ideas and useful tools to its users, clients, and stakeholders.

These insights stem from comprehensive research, as evidenced by the accompanying table and graphic.

<br>
| Goals               | Relevancy (0-5) | Viability (0-5) | N. Items (0-~) |
|:-------------------:|:---------------:|:---------------:|:-------------:|
| Landing page        | 5               | 5               |               |
| NFT showcase        | 5               | 2               |               |
| Marketplace         | 5               | 1               |               |
| Metamask Login      | 5               | 2               |               |
| Learn section       | 4               | 3               |               |
| Contact Section     | 5               | 5               |               |
| CTA Offers | 4             | 3               |               |
| N. Items            |                 |                 | 7             |
| Max. Points         |                 |                 | 35            |
| Results             | 33              | 21              |               |
| Percentage          | 94.28% <br> (Strategy)| 60% <br> (Scope)     |               |
<br>

![Table Graphic](https://github.com/plexoio/morada/blob/main/assets/img/strategy.png)

The results show that the points we selected for our 'Relevancy' group are integrated with the most important points for the project itself, with the `Learn` and `CTA Offers` points having a slight difference of `4` to `5` compared to the highest point.

In terms of viability, things started getting serious enough for us to see what we can really accomplish within the given time frame, with the technologies in use and the resources available. Among the 7 points, only 2 points scored a perfect `5` out of `5`, with `Learn` scoring the highest after the ones already mentioned, at `3`.

Taking into account the other points for `Viability`, we arrive at a percentage that represents our possible contribution to this idea based on factors such as time, technology, and resources. From a different perspective, this tells us that we can complete at least 60% of this project, with the other 40% requiring greater investments in time and human resources.

Based on these percentages, I have written a `Strategy` for `Relevancy` and a `Scope` for `Viability`, as these results can help us understand our overall `Strategy` and the upcoming `Scope` planning, since they are all interrelated.

With this information, we can now move on to the next stage, which is `Scope`.

<hr>

## What's new?

- General improvements in user experience and interface.

- First Jigsaw W3C testing: all valid, no errors. Badge added to the footer.

- New HTML W3C testing: all valid, no errors.

- Finished contact section and added social media buttons.

- Successfully installed Metamask login using the Web3 JavaScript library.

- Added social media buttons to the `index.html` footer and `contact.html` pages.

- Styled the input elements with a cursor: `pointer`.

Bugs or errors are still expected.


## What's coming?

- Improvements to the user experience of `learn.html`

- Responsiveness

- Accessibility

- Security

- Efficiency (`optimization`)

- Addressing the call-to-action issue (still pending)

I am still building the final code structure. More versions are coming!


## Roadmap

- Create main `index.html`, `learn.html`, `marketplace.html`, `contact.html`, `style.css`, and `nft.css` files

- Organize the web app's structure properly

- Add images or Lottie files and related content for better interpretation

- Add structural files and documents to appropriate folders and subfolders

- Layouts

- Accessibility

- Anchor security: `rel` attribute and values

- W3C testing

- Apply learned content more on DOM selectors, semantics, selectors, CSS implementation, measurements, font, colors, etc.

- Responsiveness

- UE/UI high performance


## Actual Features

- Full-stack boilerplate
- Completely runnable
- Semi-responsive design
- Structured comments in code

## Visual Structure

Intended logical organization of the code

**morada**/

├── index.html

├── marketplace.html

├── learn.html

├── contact.html

├── **assets**/

│ &nbsp;&nbsp;&nbsp;└── css/

│       &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;├── style.css

│       &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;├── nft.css

│ &nbsp;&nbsp;&nbsp;└── font/

│    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;└── Bitter/

│    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;└── Lora/

│    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;└── Roboto/

│ &nbsp;&nbsp;&nbsp;└── img/

│       &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;├── logo.png

│ &nbsp;&nbsp;&nbsp;└── js/

├── **documentation**/

├── **vendor**/

│   └── img/

│       &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;├── hero.jpg

│       &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;├── marketplace.jpg

│       &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;└── sample.jpg


## FAQ

#### Is the structure already finished?

Once the entire project has been deployed, the structure section may be considered as complete.

#### Are there issues in it?

Once the entire project has been deployed, we will add a note with all passed tests for security, accessibility, quality, and semantics.

## Credits

- sample.jpg: [@jjjordan](https://unsplash.com/@jjjordan)
- hero.jpg: [@naimbic](https://www.pexels.com/@naimbic)
- marketplace.jpg: [@Rodion Kutsaiev](https://unsplash.com/photos/-tgTipG2t_g)
- Rather than relying on Stack Overflow or Google for all my programming queries, I specifically turned to **ChatGPT** to seek clarification on certain code implementations and clear up any lingering doubts.
- [codeinstitute.net](https://codeinstitute.net/) for the proper education provided, which knowledge is being applied throughout this project.
- Programminghub where I learned the basics before joining Code Institute.

## Authors 

- [@plexoio](https://www.github.com/plexoio) | Frank Arellano
