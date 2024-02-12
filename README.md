= Abstract =

The project, named Magpie, is a Python-based application that implements symmetric encryption and hashing techniques to secure text messages. It provides both a command-line interface (CLI) and a graphical user interface (GUI) for users to enter, encrypt, decrypt, and verify text messages using a secret key. The application utilizes the shift cipher for encryption and the SHA-256 algorithm for hashing.

The main objective of the project is to demonstrate the fundamental principles of cryptography and information security in a simple and interactive manner. It includes a tutorial and a README file that explain the concepts and usage of the application.

== Features ==
- Symmetric encryption using the shift cipher
- Hashing using the SHA-256 algorithm
- Command-line interface (CLI) for text message operations
- Graphical user interface (GUI) for easy interaction
- Secret key-based encryption and decryption
- Text message verification
- Tutorial and README files for guidance

== Purpose ==
The purpose of the Magpie project is to provide a practical example of how symmetric encryption and hashing techniques can be used to secure text messages. By implementing a command-line interface and a graphical user interface, the project aims to make the concepts of cryptography and information security more accessible to users. The tutorial and README files further enhance the understanding of the application's concepts and usage.

== Conclusion ==
Magpie is a Python-based application that showcases the implementation of symmetric encryption and hashing techniques for securing text messages. With its command-line interface, graphical user interface, and comprehensive documentation, the project serves as an educational tool for understanding the basic principles of cryptography and information security.



# HTML, CSS, JS (Auto Refresh)

This template is a starter for building a website with HTML, CSS and JS, powered by [Vite](https://vitejs.dev/). HTML provides the basic structure, CSS controls formatting, and JavaScript controls the behavior of different elements.

Hit run to see this project in action. It will auto-refresh as you edit the HTML, CSS and JS files.

## Disable Auto Refresh

If you find the auto refresh getting in your way, go to [vite.config.js](./vite.config.js) and update it set `hmr` to false to disable hot module reloading (HMR). The full config will look like this:

```js
export default defineConfig({
  plugins: [],
  server: {
    host: '0.0.0.0',
    hmr: false, // Change this line to `false` disable auto-refreshing.
  }
})
```

## Packages

Because this template uses Vite to build your code, you can add install and use npm packages. Simple open the Packager tool to search and manage your packages.

## Learn More

Check out [the vite docs](https://vitejs.dev) to learn more about configuring a frontend application.
