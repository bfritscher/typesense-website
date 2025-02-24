# Installing a client

We have client libraries for:

- [JavaScript](https://github.com/typesense/typesense-js)
- [PHP](https://github.com/typesense/typesense-php)
- [Python](https://github.com/typesense/typesense-python)
- [Ruby](https://github.com/typesense/typesense-ruby)

We also have the following community-maintained client libraries:

- [Go](https://github.com/typesense/typesense-go)
- [.Net](https://github.com/DAXGRID/typesense-dotnet)
- [Java](https://github.com/typesense/typesense-java)
- [Rust](https://github.com/typesense/typesense-rust)
- [Dart](https://github.com/typesense/typesense-dart)
- [Perl](https://github.com/Ovid/Search-Typesense)
- [Swift](https://github.com/typesense/typesense-swift)
- [Clojure](https://github.com/runeanielsen/typesense-clj)

We also have several framework integrations listed [here](https://typesense.org/docs/latest/api/api-clients.html#framework-integrations).

:::tip
If you don't see an official client in your language, you can still use any HTTP library / package in your language to make API calls to Typesense's REStful API.
:::

<br>

<Tabs :tabs="['JavaScript','PHP','Python','Ruby']">
  <template v-slot:JavaScript>

```js
// npm install typesense @babel/runtime

// Browser
<script src="dist/typesense.min.js"></script>
```

  </template>

  <template v-slot:PHP>

```shell
composer require php-http/curl-client typesense/typesense-php
```

  </template>
  <template v-slot:Python>

```shell
pip install typesense
```

  </template>
  <template v-slot:Ruby>

```shell
gem install typesense
```

  </template>
</Tabs>
