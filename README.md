#, diablo-assistent
App om spelers te assisteren tijdens het spelen van Diablo 2.

### Runewords - GraphQL
```javascript
// Add runeword "Insight"
{
  runeword
  {
    name : "Insight"
    runes : [(name: "Ral"),(name: "Tir"),(name: "Tal"),(name: "Sol")]
  }
}

// Get runes for runeword "Insight"
{
  runeword(name: "Insight")
  {
    runes
  }
}

// Get runes for runes "Tir" and "Tal" 
{
  runeword
  {
    name
    runes : [(name: "Tir"),(name: "Tal")]
  }
}
```


