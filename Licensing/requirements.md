# Apache 2.0 Licensing Requirements

This guide outlines the requirements for ensuring your repository properly adheres to Apache 2.0 licensing standards.

## Required Files

### 1. LICENSE File
- Must be placed in the root directory
- Must contain the complete Apache 2.0 license text
- Must be named `LICENSE` (uppercase, no file extension)
- Must not be modified from the original Apache 2.0 text

### 2. NOTICE File
- Must be placed in the root directory
- Must be named `NOTICE` (uppercase, no file extension)
- Must include:
  - Copyright statements
  - Your organization name
  - Any required attributions for third-party software
  - Any additional notices required by your organization

## Source Code Requirements

### License Headers
All source code files must include the Apache 2.0 license header with appropriate comment syntax:

#### Docker Files (`Dockerfile`, `docker-compose.yml`)
```yaml
# Copyright 2025 Ontario Institute for Cancer Research
#
# Licensed under the Apache License, Version 2.0 (the "License");
# you may not use this file except in compliance with the License.
# You may obtain a copy of the License at
#
#     http://www.apache.org/licenses/LICENSE-2.0
#
# Unless required by applicable law or agreed to in writing, software
# distributed under the License is distributed on an "AS IS" BASIS,
# WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
# See the License for the specific language governing permissions and
# limitations under the License.
```

#### Other Source Files (`.js`, `.java`, `.cpp`, etc.)
```java
/*
   Copyright 2025 Ontario Institute for Cancer Research

   Licensed under the Apache License, Version 2.0 (the "License");
   you may not use this file except in compliance with the License.
   You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

   Unless required by applicable law or agreed to in writing, software
   distributed under the License is distributed on an "AS IS" BASIS,
   WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
   See the License for the specific language governing permissions and
   limitations under the License.
*/
```

#### Python Files (`.py`)
```python
"""
   Copyright 2025 Ontario Institute for Cancer Research

   Licensed under the Apache License, Version 2.0 (the "License");
   you may not use this file except in compliance with the License.
   You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

   Unless required by applicable law or agreed to in writing, software
   distributed under the License is distributed on an "AS IS" BASIS,
   WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
   See the License for the specific language governing permissions and
   limitations under the License.
"""
```

## Files to Exclude
Do NOT add license headers to:

1. Configuration Files:
   - `.env`
   - `.gitignore`
   - `.editorconfig`
   - `requirements.txt`
   - `package.json`
   - `poetry.lock`
   - `Pipfile`/`Pipfile.lock`

2. Data Files:
   - `.json`
   - `.csv`
   - `.xml` data files

3. Documentation:
   - `README.md`
   - `CHANGELOG.md`
   - `CONTRIBUTING.md`

4. Generated Files:
   - Auto-generated code
   - Build outputs
   - Log files

## Automation Tools

We provide a script (`add-headers.js`) to automatically add license headers to your source files. To use it:

1. Copy the script to your project root
2. Run: `node add-headers.js`

The script will:
- Add appropriate license headers to all relevant files
- Skip already licensed files
- Use the correct comment syntax for each file type
- Skip excluded files and directories

## Checklist for Compliance

- [ ] LICENSE file in root directory
- [ ] NOTICE file in root directory
- [ ] License headers in all source code files
- [ ] Headers use correct comment syntax for each language
- [ ] Third-party attributions listed in NOTICE file
- [ ] Configuration and data files excluded
- [ ] Copyright year and organization name updated

## Additional Resources

- [Apache License 2.0 Full Text](http://www.apache.org/licenses/LICENSE-2.0)
- [Apache License Policy](https://www.apache.org/legal/resolve.html)
- [How to Apply Apache License](https://www.apache.org/foundation/license-faq.html)