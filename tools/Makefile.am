## Copyright 2021 University of Adelaide

## Licensed under the Apache License, Version 2.0 (the "License");
## you may not use this file except in compliance with the License.
## You may obtain a copy of the License at

##    http://www.apache.org/licenses/LICENSE-2.0

## Unless required by applicable law or agreed to in writing, software
## distributed under the License is distributed on an "AS IS" BASIS,
## WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
## See the License for the specific language governing permissions and
## limitations under the License.

LDADD = -lassemblyline
AM_LDFLAGS = -L$(top_srcdir)/src
AM_CPPFLAGS = -I$(top_srcdir)/src/
AM_CFLAGS = -Wall -std=gnu99

bin_PROGRAMS = asmline
asmline_SOURCES = asmline.c
dist_man1_MANS = asmline.1
