#Inline and Inline-Block Vertial Align

##Single Line
-can appear vertically centering due to equal padding above and below
-if padding not an option, make line-height equal to the height to center text

##Multiple Lines
-can use same equal padding technique as above
-can also use vertical-align property
 -is dependent on line height
 -applies to elements being aligned, not their parent element
-flex: parent container needs fixed height

```
.flex-center-vertically {
  display: flex;
  justify-content: center;
  flex-direction: column;
  height: 400px;
}
```

-ghost-element technique: places a full-height pseudo element inside the container to vertically center text

##Block-Level Element
-flexbox is easiest
```
.parent {
  display: flex;
  flex-direction: column;
  justify-content: center;
}
```
