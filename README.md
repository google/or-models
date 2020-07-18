# OR-Models

This repository contains a models and data from the Operations Research community.

## How to Use these Models and Data Sets

1. Check it out from GitHub.
1. Explore problems and relevant data sets
1. Choose modeling option
1. Load into a jupyter notebook or a Google colab site

## Organization

Each problem type is organized in the following way

    problem/
        README.md         # Description of the problem
        data/             # Root directory of all data sets
            README.md     # Description of the data, and the file format.
            type1/        # Sub directory for licensed data
                LICENSE   # Optional license file
                data      # Data sets with a the above license
            data          # Data set with the or-models main license
        model1/           # One particular model for this problem
            model1.ipynb  # Jupyter notebook that solves the above problem

## Contributing a New Problem

First, read the contributing file and the code of conduct files in the docs/
subdirectory.

Choose a license for the content you are adding, We encourage using the
Apache license file provided at the root of this project, and add yourself to
the list of authors in the AUTHORS file.

Then create the problem sub-directory and populate it with the README.md 
file and data/ subdirectory.

If the data has different license than the main license, please put it in a
sub-directory of the data/ directory

## Contributing New Models for an Existing Problem

First, read the contributing file and the code of conduct files in the docs/
subdirectory.

Choose a license for the content you are adding, We encourage using the
Apache license file provided at the root of this project, and add yourself to
the list of authors in the AUTHORS file.

Then create the problem sub-directory of the problem/ structure and add the
relevant jupyter notebook. Do not forget to add the project license to the file.

## Contributing New Data for an Existing Problem

First, read the contributing file and the code of conduct files in the docs/
subdirectory.

If you agree with the main or-models license, you can add the dataset directly
in the data/ subdirectory of the problem. You always have the option to create a
subdirectory if needed.

If you want to use another license, first make sure that the data will be usable
for any person interested. Then create a subdirectory of the data/ directory,
add the license file, and then the complete dataset.

## Source Code Headers

Every file containing source code must include copyright and license
information. This includes any JS/CSS files that you might be serving out to
browsers. (This is to help well-intentioned people avoid accidental copying that
doesn't comply with the license.)

Apache header:

    Copyright 2020 The or-models Authors.

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        https://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
