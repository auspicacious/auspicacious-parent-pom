# Auspicacious parent POM

Writing consistent, maintainable code in any programming language is hard. Java is lucky in that it has a wide variety of static analysis tools available to help enforce consistent style, avoid common pitfalls, detect when duplicate classes might lead to classloader conflicts, find security issues, and ensure the correct versions of dependencies are used. This POM tries to use as many of these tools as possible.

All of this static analysis runs by default and creates failures by default, to encourage issues to be fixed early in the process. However, it is possible to disable most of it, by passing `-DdisableSafeties` on the command line.

## License

Copyright (C) 2019-2020 Andrew Todd at@auspicacious.org

This program is free software: you can redistribute it and/or modify
it under the terms of the GNU Affero General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU Affero General Public License for more details.

You should have received a copy of the GNU Affero General Public License
along with this program.  If not, see <https://www.gnu.org/licenses/>.
