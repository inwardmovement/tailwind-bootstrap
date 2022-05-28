To make Tailwind 3 play nicely with Bootstrap 5, update Tailwind config file with these options:

```
module.exports = {
  ...
  prefix: "tw-",
  important: true,
  corePlugins: {
    preflight: false
  },
  ...
  theme: {
    screens: {
      "xs": "0",
      "sm": "576px",
      "md": "768px",
      "lg": "992px",
      "xl": "1200px",
      "2xl": "1400px"
    },
  ...
}
```

Source: [Adding Tailwind CSS to an Existing Project](https://www.youtube.com/watch?v=oG6XPy1t1KA)
