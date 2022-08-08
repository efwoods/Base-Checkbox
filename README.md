# Base-Checkbox
Base Checkbox Component

## Purpose
Reusable Checkbox Component

## Explaination
[Vue Mastery: BaseCheckbox](https://www.vuemastery.com/courses/vue3-forms/base-checkbox)

[BaseCheckbox.vue](./BaseCheckbox.vue)

- event structure (defined in App)
```
      event: {
        category: '',
        title: '',
        description: '',
        location: '',
        pets: 1,
        extras: {
          catering: false,
          music: false
        }
      }
```

## Prerequisites
None

## Use
```
        <BaseCheckbox
          v-model="event.extras.catering"
          label="Catering"
        />
```


[<BaseCheckbox v-model="event.extras.catering" label="Catering"/](https://gist.githubusercontent.com/efwoods/ea8d10c27ad2be109d75f607688fbe78/raw/a9af4127757421f9804e3ebc45a709a4f37af18d/BaseCheckbox.vue)
