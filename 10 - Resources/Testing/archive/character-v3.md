%%

---
aliases:
  - 
cssclasses:
  - chara
  - wide
  - wide-tabs
tags:
  - character
  - "#character/major"
image: `"![[cafelogobig.png]]"`
age: 0
birthday: Month 00th
gender: ♀/♂/⚲ (pro/noun)
sexuality: Sexuality
occupation: Job
affiliates:
  - `"[[group]]"`
height: 0'0"
affinity: Affinity
nationality: Nationality
creator: Creator
quote: Something your funny guy would say
---
%%

> [!chara]
> # `=this.file.name`
> | `=this.age` • `=this.gender` • `=this.sexuality` | `=this.occupation`|
| --- | --: |

> [!multi-column]
> > [!img]
> > 
> > `=this.image`
> 
> > [!desc]
> > > [!blockquote] 
> > > ❝ `=this.quote` ❞
> > 
> > | Key | Value |
| --- | --: |
| Birthday | `=this.birthday` 
| Height | `=this.height` |
| Affinity | `=this.affinity` |
| Nationality | `=this.nationality` |
| Creator | `=this.creator` |
> > 

<br>

~~~tabs
tab: Personality
> [!blockquote] 
> adjective **•** adjective **•** adjective

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. 
<br><br>
````col
```col
- :LiCircleCheck: **Pos Trait**: Lorem ipsum dolor sit amet
- :LiCircleCheck: **Pos Trait**: Lorem ipsum dolor sit amet
- :LiCircleCheck: **Pos Trait**: Lorem ipsum dolor sit amet
```
```col
- :LiCircleX: **Neg Trait**: Lorem ipsum dolor sit amet
- :LiCircleX: **Neg Trait**: Lorem ipsum dolor sit amet
- :LiCircleX: **Neg Trait**: Lorem ipsum dolor sit amet
```
tab: Trivia
- Random
- Facts 
- About
- Them

tab: Mannerisms
> [!multi-column]
> 
> >[!quote] Speech Patterns
> > - Habit
> > - Habit
> > - Habit
> > 
> > **Examples**
> > - Ex
> > - Ex
> > - Ex
> 
> > [!tip] Body Language
> > - Thing
> > - Thing
> > - Thing
> 
> > [!warning] No-Nos
> > Things they would never do
> > - Thing
> > - Thing 
> > - Thing
~~~


## Bio 

### Section
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

## Relationships
%% Relationship 01 %%
>[!col] 
>> [!r-img]
>> `=[[character]].image`
>
>>> [!r-desc]
>>>`[[character-v3]]` <small>[Relation]</small> - *Quote* 
>>> --- 
>>>  Lorem ipsum dolor sit amet, consectetur adipiscing elit.

%% Relationship 02 %%
>[!col] 
>> [!r-img]
>> `=[[character]].image`
>
>>> [!r-desc]
>>> `[[character-v3]]` <small>[Relation]</small> - *Quote* 
>>> --- 
>>>  Lorem ipsum dolor sit amet, consectetur adipiscing elit.

### Other Relationships
- `[[character-v3]]`: Relation
- `[[character-v3]]`: Relation
- `[[character-v3]]`: Relation

## Links

### Affiliates
```dataview
LIST WITHOUT ID affiliates
WHERE file = this.file 
FLATTEN affiliates
```

### Stories
```dataview
LIST WITHOUT ID story
FROM "01 - Stories" 
WHERE contains(characters, [[]]) 
FLATTEN stories 
```