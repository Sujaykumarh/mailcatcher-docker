# MailCatcher Docker-compose

MailCatcher is better open-source alternative to [mailtrap.io](https://mailtrap.io/)

MailCatcher runs a super simple SMTP server which catches any message sent to it to display in a web interface. Run mailcatcher, set your favourite app to deliver to `smtp://127.0.0.1:1025` instead of your default SMTP server, then check out `http://127.0.0.1:1080` to see the mail.
 

<br>

### TODO

- [ ] update image to latest mailcatcher version

<br>
<br>

### Sources

- mailcatcher website :point_right: [mailcatcher.me](https://mailcatcher.me/)

- mailcatcher source :point_right: [GitHub](https://github.com/sj26/mailcatcher)

- docker image :point_right: [schickling/mailcatcher](https://hub.docker.com/r/schickling/mailcatcher)

- source :point_right: [schickling/dockerfiles](https://github.com/schickling/dockerfiles/tree/master/mailcatcher)

- [Docker Documentation](https://docs.docker.com)

- [Docker Compose Documentation](https://docs.docker.com/compose/)

- `mailtrap.io` guide :point_right: [mailcatcher-guide](https://blog.mailtrap.io/mailcatcher-guide/)

<br>

# LICENSE

    MIT License

    Copyright (c) 2020 Sujaykumar Hublikar

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
