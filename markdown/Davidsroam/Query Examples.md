- Recently assigned
    - ```javascript
{{[[query]]: {and: [[TODO]] {not: {or: [[Today]] [[Upcoming]] [[Later]] [[Template]] [[query]]]}}}}}```
- Today
    - ```javascript
{{[[query]]: {and: [[TODO]] [[Today]] {not: {or: [[Template]] [[query]]]}}}}}```
- Upcoming
    - ```{{[[query]]: {and: [[TODO]] [[Upcoming]] {not: {or: [[Template]] [[query]]]}}}}}```
- Later
    - ```{{[[query]]: {and: [[TODO]] [[Later]] {not: {or: [[Template]] [[query]]]}}}}}```
- ToDo
    - ```javascript
{{[[query]]: {and: [[TODO]] {not:{or: [[query]] [[test page]] [[Templates]]} } }}}```
- Live list
- {{[[query]]: {and: [[Livelist]] [[TODO]]}}}
- ## Books for which highlights have been processed
- {{[[query]]: {and: [[Books]] [[Evergreens]]{not: {between: [[January 1st, 2020]] [[January 1st, 2021]]}}}}}
- {{[[query]]: {and: [[Books]] [[ToRead]]}}}
