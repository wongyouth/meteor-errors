An alert box will show 3 seconds then hide after your throw an error.

## Add meteor-errors to your project

    meteor add wongyouth:errors

## Usage

### add error

    Errors.throw('your error message here')

### show errors

add to your html layout

```html

<header>...</header>
{{> meteor-errors}}

<div class="container">
  ...
</div>

```

## Styling animation

```
@keyframes fadeOut {
  0% {opacity: 0;}
  10% {opacity: 1;}
  90% {opacity: 1;}
  100% {opacity: 0;}
}

.alert {
  animation: fadeOut 2700ms ease-in 0s 1 forwards;
}
```
