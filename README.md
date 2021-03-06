## BadCode

BadCode is a static source code scanner that fingerprints bad security practices and identify them.

![This screenshot shows a bunch of SQL injections in some Wordpress plugins by only using regex to detect them.](https://raw.githubusercontent.com/pwnsdx/BadCode/master/screenshot.png)

###### This screenshot shows a bunch of SQL injections in some Wordpress plugins by only using regex to detect them.

### Want to see how people code their plugins so badly?

1. Download a huge repository of files (see [repositories.yaml](https://github.com/pwnsdx/BadCode/blob/master/repositories.yaml))
2. Open the folder that contains the files in *Sublime Text* and "Find in Files" the regex of your choice (see [alpha.yaml](https://github.com/pwnsdx/BadCode/blob/master/alpha.yaml))
3. Enjoy!

### This is just the beginning

- More regular expressions for PHP and Wordpress (based on OWASP documentation) in progress
- Joomla! support is coming
- Drupal support is coming
- Many PHP frameworks support are coming
- CLI that check files automatically is coming too!
- Other languages?

**Note: This project won't save you from every security issues and especially intentional backdoor as the code can be obfuscated to bypass the detection.**

### Contributing

Any help is very appreciated, especially in these areas:

- Regex (by adding new ones or fixing/optimizing the existing ones)
- Repositories (by adding more of them)

All pull requests that is considered useful will be accepted.

#### License

```
The MIT License (MIT)

Copyright (c) 2016 Sabri Haddouche <https://pwnsdx.pw/>

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```
