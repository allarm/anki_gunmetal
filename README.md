# Anki Gunmetal

An anti-ugly theme for Anki. 

## Templates
### Front Template

```html
<div class="body">
<div class="context">{{Context}}</div>
<div class="p">{{cloze:Text}}</div>
<div class="source">{{Source}}</div>
</div>
```

### Back Template

```html
<div class="body">
<div class="context">{{Context}}</div>
<div class="p">{{cloze:Text}}</div>
{{#Back Extra}}
<div class="back_extra">{{Back Extra}}</div>
{{/Back Extra}}
{{#Mnemonics}}
<div class="mnemonics">{{Mnemonics}}</div>
{{/Mnemonics}}
<div class="source">{{Source}}</div>
</div>
```

## Screenshots
### Laptop

![laptop front](/screenshots/laptop_front.png)
![laptop back](/screenshots/laptop_back.png)

### Mobile

<img src="https://raw.githubusercontent.com/allarm/anki_gunmetal/master/screenshots/mobile_front.png" width=50%>
<img src="https://raw.githubusercontent.com/allarm/anki_gunmetal/master/screenshots/mobile_back.png" width=50%>

## Test Anki Deck

[deck](test_deck.apkg)

## Credits

Andrey Che
