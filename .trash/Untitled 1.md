---
aliases:
  - "%% list of nicknames used for links %%"
cssclasses:
  - chara
  - wide
  - wide-tabs
tags:
  - character
  - "#character/major"
image: cafelogobig.png
age: 0
birthday: Month 00th
gender: ♀/♂/⚲ (pro/noun)
sexuality: Sexuality
occupation: Job
affiliates:
  - "[[group]]"
  - "[[group]]"
  - "[[group]]"
family:
  - "[[character]]"
  - "[[character]]"
  - "[[character]]"
height: 0'0"
affinity: Affinity
nationality: Nationality
creator: Creator
quote: Something your funny guy would say
---
> [!infobox] 
> `=this.image`
> `=this.age` **•** `=this.gender` **•** `=this.height`
> ---
 >> [!blockquote]  
 >> "`=this.quote`"
> ---
> <span class="l">Age</span> `=this.age` 
> <span class="l">Birthday</span> `=this.birthday` 
> <span class="l">Height</span>  `=this.height`
> <span class="l">Affinity</span>  `=this.affinity` 
> <span class="l">Nationality</span> `=this.nationality`
> <span class="l">Creator</span> `=this.creator`
> # Affiliates
> 
> ```dataview
> LIST WITHOUT ID affiliates
> WHERE file = this.file 
> FLATTEN affiliates
> ```
>
> # Family
> 
> ```dataview
> LIST WITHOUT ID family
> WHERE file = this.file 
> FLATTEN family
> ```

---
> [!blockquote] 
> adjective **•** adjective **•** adjective

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. 

## Strengths and Weaknesses
---
<br>

````col

```col
- [p] pos trait
- [p] pos trait
- [p] pos trait
```

```col
- [c] neg trait
- [c] neg trait
- [c] neg trait
```

````



## Bio 
---
### Section
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

## Relationships
---
%% Relationship 01 %%
>[!col] 
>> [!r-img]
>> `=[[character]].image`
>
>>> [!r-desc]
>>>[[character-v3]] <small>[Relation]</small> - *Quote* 
>>> --- 
>>>  Lorem ipsum dolor sit amet, consectetur adipiscing elit.

%% Relationship 02 %%
>[!col] 
>> [!r-img]
>> `=[[character]].image`
>
>>> [!r-desc]
>>> [[character-v3]] <small>[Relation]</small> - *Quote* 
>>> --- 
>>>  Lorem ipsum dolor sit amet, consectetur adipiscing elit.

### Other Relationships
- [[character]]: Relation
- [[character]]: Relation
- [[character]]: Relation

## Links
---
### Stories
```dataview
LIST WITHOUT ID story
FROM "01 - Stories" 
WHERE contains(character, [[]]) 
FLATTEN stories 
```