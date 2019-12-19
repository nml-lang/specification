# For loop property

## Discription
Can be compared to a foreach loop in other languages.
For loop property repeats the element its on making multiple instances of that element.
Iterator variable can be used within element.
Variable can decontructed with in variabe list.

## Example

```nml
{
    link { (( name, link, level), i ) in links }: {
        text: name;
        to: link;
        tag { i == this.route.i }: active;
    }
}
```
