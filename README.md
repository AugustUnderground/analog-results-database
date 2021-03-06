# analog-results-database

Analog Result Database

## Dependencies

The following dependencies must be installed manually:

- [nutmeg-reader](https://github.com/electronics-and-drives/nutmeg-reader) 

Clone the corresponding repositories, enter the directory and execute

```bash
$ mvn install
```
## Setup

### Java
Add the dependency to your project

```xml
<dependency>
  <groupId>edlab.eda</groupId>
  <artifactId>analog-results-database</artifactId>
  <version>0.0.1</version>
</dependency>
```

Import the corresponding package to your code
```java
import edlab.eda.ardb.*;
```

## API

### Java

The [JavaDoc](https://matthschw.github.io/analog-results-database/)
is stored on the Github-Pages (branch *gh-pages*).

## TODO

- Finish [JavaDoc](https://matthschw.github.io/analog-results-database/)
- Add more waveform processing functions

## License

Copyright (C) 2021, [Electronics & Drives](https://www.electronics-and-drives.de/)

This program is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with this program. If not, see 
[https://www.gnu.org/licenses/](https://www.gnu.org/licenses).