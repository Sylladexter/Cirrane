---
type: character
creator: Creator
relevance: Major | Secondary | Minor
location: 
tags:
  - character
image: "![[cafelogobig.png]]"
job: 
age: 0
birthday: Month 00th
gender: 
sexuality: 
height: 
affinity: 
nationality: 
affiliates:
  - "[[Affiliate 01]]"
  - "[[Affiliate 02]]"
  - "[[Affiliate 03]]"
  - "[[affiliation]]"
stories: "%% place query for stories %%"
---
> [!infobox]
> ### `=this.file.name`
> `=this.image`
> ### `=this.job`
> | Type | Stat |
> | --- | --- |
> | Age | `=this.age` |
> | Birthday | `=this.birthday` |
> | Gender | `=this.gender` |
> | Sexuality | `=this.sexuality` |
> | Height | `=this.height` |
> | Affinity | `=this.affinity` |
> | Nationality | `=this.nationality`|
> | Creator | `=this.creator` |
> 
> ### Affiliates 
> ```dataview
> LIST WITHOUT ID affiliates
> WHERE file = this.file 
> FLATTEN affiliates
> ```
> 
> ### Stories
> ```dataview
> LIST WITHOUT ID story
> FROM "01 - Stories" 
> WHERE contains(characters, [[]]) 
> FLATTEN stories 
> ```
---

> [!quote] 
> Something your funny guy would say

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

## Bio 
---
#### Section
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.