# vCard-Json.js
It's a simple but powerful decoder tool that loads your data from vCards strings and returns fully categorized Json.

## How to use 

```javascript
  let $vCard = 'BEGIN:VCARD\nVERSION:3.0\nN:Gump;Forrest;;Mr.;\nFN:Forrest Gump\nORG:Bubba Gump Shrimp Co.\nTITLE:Shrimp Man\nTEL;TYPE#WORK,VOICE:(111) 555-1212\nTEL;TYPE#HOME,VOICE:(404) 555-1212\nADR;TYPE#WORK,PREF:;;100 Waters Edge;Baytown;LA;30314;United States of America\nLABEL;TYPE#WORK,PREF:100 Waters Edge\nBaytown\, LA 30314\nUnited States of America\nADR;TYPE#HOME:;;42 Plantation St.;Baytown;LA;30314;United States of America\nLABEL;TYPE#HOME:42 Plantation St.\nBaytown\, LA 30314\nUnited States of America\nEMAIL:forrestgump@example.com\nREV:2008-04-24T19:52:43Z\nEND:VCARD'
  
  vCard.initialize($vCard).to_json();  
```

And the result is:

![image](https://user-images.githubusercontent.com/26697873/233867606-ef3849fd-5e42-4c0d-a73f-7fb89d19d35d.png)


## Copyright and license

Code released under the [MIT license](https://github.com/jeankassio/LBT-Lightbox/blob/main/LICENSE).
