# jToast
A very simple to use jQuery Plugin to create Toasts.

## Demo
[Click](https://l2g.cc/projects/jToast/)

## Customization options
* Text
* Duration
* Background
* Color
* Border radius

## Usage & default values
```javascript
showToast(text, {
  duration: 3000,
  background: '#232323',
  color: '#fff',
  borderRadius: 0
});
```

## An example
```javascript
showToast('WHAT'S UP?!', {
  duration: 5000,
  background: '#0769ad',
  color: '#f1f1f1',
  borderRadius: 15
});
