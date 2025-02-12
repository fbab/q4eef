# q4eef

# Quizz taxonomies

<!-- if needed, a nicer edition is possible by copy-paste on https://www.tablesgenerator.com/markdown_tables -->
| tools>                   | quizizz     | moodle          | kahoot | wooclap        | mentimeter | digitaliser |
|--------------------------|-------------|-----------------|--------|----------------|------------|-------------|
| multiple choice question | OK          | OK              | OK     |                | 2          |             |
| One choice question      |             |                 | OK     |                | 2          |             |
| true/false               | $           | OK              | OK     |                | 2          |             |
| matching                 | $ drag&drop | dropdown merged | N/A    | radio unmerged | N/A        |             |
| open                     |             | OK              |        |                |            |             |

# Reuser tools

# Creator tools

|         | type(s)   | format preferred (first) | preferred (second) |
|---------|-----------|-------------------|--------------------|
| moodle  | MCQ       | aiken             | moodle_xml         |
|         | Matching  | moodle_xml        |                    |
| quizizz | MCQ       | [quizizz Excel](doc/export_from_quizizz.md)     |                    |
|         | Matching$ | not tested            |                    |

## Storage repository : pivots
The file exported from the creator tool has to be stored in the [__pivots__](https://github.com/frederic-baucher/q4eef/tree/main/bank) directory of this Github repository. Any additional file (for instance, images) has to be stored in the same place. All the files must follow the __q4eef naming convention__.

## Naming convention : q4eef
Any exported exercise file __MUST__ have a name __COMPLIANT__ with the naming convention.

### Pattern
- $\textcolor{red}{\text{creator}}\textcolor{orange}{\text{id}}\textcolor{black}{\text{.}}\textcolor{grey}{\text{label}}\textcolor{black}{\text{[-}}\textcolor{blue}{\text{lang}}\textcolor{black}{\text{][.}}\textcolor{pink}{\text{type}}\textcolor{black}{\text{][.}}\textcolor{green}{\text{format}}\textcolor{black}{\text{].}}\textcolor{purple}{\text{extension}}$
### Example
- $\textcolor{red}{\text{EXG}}\textcolor{orange}{\text{1472}}\textcolor{black}{\text{.}}\textcolor{grey}{\text{serious-games}}\textcolor{black}{\text{.}}\textcolor{green}{\text{aiken}}\textcolor{black}{\text{.}}\textcolor{purple}{\text{txt}}$
  - a file containing an exercise (by default, the type is mcp and the language is english) created in the EXG repository, under id 1472.
- $\textcolor{red}{\text{EXG}}\textcolor{orange}{\text{2131}}\textcolor{black}{\text{.}}\textcolor{grey}{\text{scrum-in-essence-constructs}}\textcolor{black}{\text{-}}\textcolor{blue}{\text{fr}}\textcolor{black}{\text{.}}\textcolor{pink}{\text{matching}}\textcolor{black}{\text{.}}\textcolor{green}{\text{aiken}}\textcolor{black}{\text{.}}\textcolor{purple}{\text{txt}}$
  - a file containing a matching exercise in AIKEN format stored in a txt file
- $\textcolor{red}{\text{EXG}}\textcolor{orange}{\text{2131}}\textcolor{black}{\text{.}}\textcolor{grey}{\text{scrum-in-essence-constructs}}\textcolor{black}{\text{-}}\textcolor{blue}{\text{fr}}\textcolor{black}{\text{.}}\textcolor{purple}{\text{png}}$
  - a file containing an image localised in french to be used with exercise EXG2131
### Legend
- $\textcolor{red}{\text{creator}}$ : creator question bank identifier (upper case alphabets [A-Z]), as registered in the table below
- $\textcolor{orange}{\text{id}}$ : id of the exercise (upper case numbers [0-9], unique inside the creator repository)
- $\textcolor{grey}{\text{label}}$ : label (only low-case alphabets [a-z] underscore separated if necessary)
- $\textcolor{blue}{\text{lang}}$ : language code compliant with ISO 639-1 (default : en)
- $\textcolor{pink}{\text{type}}$ : type of exercise (default : mcq) 
- $\textcolor{green}{\text{format}}$ : logical format name (among the format list)
- $\textcolor{purple}{\text{extension}}$ : technical format name (xlsx, txt, csv, ...)

## Registered creators
To  let any creator choose its identification numbering of exercise (and yet have a unique id for any exercise in q4eef), a creator MUST have a creator id. This table list the creators already registered. To add a new creator, request a write access to this Github repository and edit the table below in [this README.md file](https://github.com/frederic-baucher/q4eef/edit/main/README.md).

<!--
How to color text in README.md

$\textcolor{red}{\text{EXG}}\textcolor{orange}{\text{1472}}\textcolor{black}{\text{.}}\textcolor{grey}{\text{serious}}$
_
$\textcolor{grey}{\text{game}} \textcolor{black}{\text{-}}\textcolor{blue}{\text{en}}\textcolor{black}{\text{.}}\textcolor{green}{\text{aiken}}\textcolor{black}{\text{.}}\textcolor{purple}{\text{txt}}$

```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```

> __Warning__
> This is a warning.

> __Note__
> This is a note.
> 
-->

