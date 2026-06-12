
# Linux Command Summary List

| Command                                            | Description                                                                                                           |
| -------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------- |
| `ls`                                               | list files and directories                                                                                            |
| `ls -lt`                                           | list all files and directories with more information about their time created and ownership, ordered from most recent |
| `mkdir`                                            | make a directory                                                                                                      |
| `cd _directory_`                                   | change to named directory                                                                                             |
| `cd`                                               | change to home-directory                                                                                              |
| `cd ~`                                             | change to home-directory                                                                                              |
| `cd ..`                                            | change to parent directory                                                                                            |
| `pwd`                                              | display the path of the current directory                                                                             |
| `cp file1 file2`                                   | copy file1 and call it file2                                                                                          |
| `mv file1 file2`                                   | move or rename file1 to file2                                                                                         |
| `rm file`                                          | remove a file                                                                                                         |
| `rmdir directory`                                  | remove a directory                                                                                                    |
| `cat file`                                         | display a file                                                                                                        |
| `more file`                                        | display a file a page at a time                                                                                       |
| `head file`                                        | display the first few lines of a file                                                                                 |
| `tail file`                                        | display the last few lines of a file                                                                                  |
| `grep 'keyword' file`                              | search a file for keywords                                                                                            |
| `wc file`                                          | count number of lines/words/characters in file                                                                        |
| `command > file`                                   | redirect standard output to a file                                                                                    |
| `command >> file`                                  | append standard output to a file                                                                                      |
| `command < file`                                   | redirect standard input from a file                                                                                   |
| `command1 \| command2`                             | pipe the output of command1 to the input of command2                                                                  |
| `cat file1 file2 > file0`                          | concatenate file1 and file2 to file0                                                                                  |
| `sort`                                             | sort data                                                                                                             |
| `*`                                                | match any number of characters                                                                                        |
| `?`                                                | match one character                                                                                                   |
| `man command`                                      | read the online manual page for a command                                                                             |
| `whatis command`                                   | brief description of a command                                                                                        |
| `apropos keyword`                                  | match commands with keyword in their man pages                                                                        |
| `command &`                                        | run command in the background                                                                                         |
| `gedit file`                                       | open a window to edit the text of file                                                                                |
| `#!/bin/tcsh`                                      | first line of a script that initializes the type of shell to be tcsh                                                  |
| `# text`                                           | allows text to just be a comment and not be treated as a command                                                      |
| `set variable=information`                         | set a shell variable to an integer or string of information                                                           |
| `chmod +x file`                                    | make the named file executable                                                                                        |
| `chmod [options] file`                             | more generally, change access rights for named file                                                                   |
| `awk options program variables file`               | awk command syntax for processing text files                                                                          |
| `pattern { action }`                               | format for an awk program text                                                                                        |
| `/text/`                                           | awk program to find lines that match text                                                                             |
| `print text`                                       | awk command to output text                                                                                            |
| `NR`                                               | awk variable that stores the line number                                                                              |
| `$number`                                          | awk character to identify column number of a text file                                                                |
| `;`                                                | character to separate commands within an awk program                                                                  |
| `sin(angle)`                                       | awk command to calculate sine of angle in radians                                                                     |
| `cos(angle)`                                       | awk command to calculate cosine of angle in radians                                                                   |
| `atan2(y,x)`                                       | awk command to calculate arctangent of y/x                                                                            |
| `command >! file`                                  | send output of command to file and overwrite file if it exists                                                        |
| `psxy filename(s) options > psfile`                | make an postscript X-Y plot from filename                                                                             |
| `-J(plot-type)(X-axis-size)/(Y-axis-size)`         | psxy option for plot size and shape                                                                                   |
| `-R(Xstart)/(Xend)/(Ystart)/(Yend)`                | psxy option for range of values                                                                                       |
| `-B(X-axis-border)/(Y-axis-border)(which-borders)` | psxy option for axis borders                                                                                          |
| `-S(symbol-type)(symbol-size)`                     | psxy option for symbol type                                                                                           |
| `-M`                                               | psxy option for plotting multiple line segments                                                                       |
| `pstext filename(s) options > psfile`              | add text to a postscript plot from filename                                                                           |
| `-K`                                               | GMT option for specifying more commands will add to the output file                                                   |
| `-O`                                               | GMT option for specifying output should be Overlayed on top of previous output                                        |

| Operator | Meaning                  |
| -------- | ------------------------ |
| <        | less than                |
| <=       | less than or equal to    |
| ==       | equal to                 |
| !=       | not equal to             |
| >=       | greater than or equal to |
| >        | greater than             |


## Shell Scripts
- in Linux system, there are several options for which Shell to use
- the commands are kept in a text file that can be made executable
	- recipe for what commands to run
## Program types: interpreted vs compiled
- Interpreted
	- easier syntax
	- more compatible across different computer types
	- shell scripts, awk, perl, python, Matlab, Javascript
- Compiled
	- relies on a compiler to convert code into something machine can execute
	- can run much faster
	- Fortran, C, C++
### Text processing with awk
- awk for processing text files
- all kinds of data available in text files
- straightfoward command format
- variety of math and spring manipulations can be performed as Actions
- works rapidly on large data-files
- awk -F":" '/linux/{print $1}'
	- field separator, pattern, action
	- $ - column
## Earthquake Catalog Introduction
- often avail in text formats

## **Workshop Overview:**

- **Duration**: Approximately **70 hours**, delivered over **12 weeks** (3 months), so **~5-7 hours per week**.
## **Course Content and Structure:**

The **12-week online workshop** includes:

- **Weekly live webinar - introductions of content** (~1 hour)
- **36 hands-on assignments**
- **Biweekly learning modules** (each with 5-8 tutorials)

## **Learning Objectives**

By the end of the workshop, participants will:

- **Develop proficiency** in scientific computing tools for seismological research.
- **Analyze seismic data** to study earthquake patterns, subsurface structures, seismic waveforms, and noise.
- **Explain seismological concepts** and how seismic data provides insights into Earth’s dynamics.
- **Build professional skills** to strengthen graduate school, internship, and job applications.

## **Core Topics Covered**

The course consists of [**six core modules**](https://serc.carleton.edu/teachearth/courses/241527.html), plus a **bonus module** on GNSS data analysis:

- **Linux & GMT** – Introduction to Linux command line, shell scripting, and basic plot generation with GMT to explore earthquake patterns in space, time, and magnitude, and Earth’s internal structure based on seismic wave travel times.
- **SAC** – Introduction to Seismic Analysis Code (SAC) for viewing seismograms as waveforms and spectrograms, conducting time-series analysis, filtering, and component rotation to detect, characterize, and interpret seismic wave patterns.
- **SAGE Data Tools** – Use of various SAGE waveform, metadata, and earthquake catalog request tools (e.g., web services, earthquake browser, Wilbur, MUSTANG, etc.) to check data availability and explore relationships between earthquakes, plate boundaries, frequency, and magnitude.
- **Waveform Visualization & Modeling** – Visualization of seismic waveforms for a given earthquake and software for forward modeling and inversion to estimate subsurface velocity structures, earthquake hypocenters, and fault plane solutions.
- **Python & ObsPy** – Introduction to Python and libraries (e.g., NumPy, Matplotlib, Pandas, and ObsPy) for retrieving, processing, and plotting seismic data tables and time series to enable rapid scientific analysis of earthquake catalogs and waveforms.
- **Jupyter Notebooks** – Use and creation of Jupyter Notebooks with Python to explain and share code for advanced seismogram processing, including removing instrument responses, calculating spectrograms, and estimating temporal changes in cultural noise.
- **(Bonus) GNSS Data Analysis** – Accessing and analyzing GNSS data, interpreting plots, creating station motion plots over time, removing linear trends, examining residuals, and exploring GNSS time series for signals of Earth processes.

## **Optional Final Assignment**

Participants will have the opportunity to:

- Select seismic recordings from anywhere in the world.
- Create a **Jupyter Notebook** to request and process the data.
- Annotate their process, detailing station selection, data processing steps, and findings.
- Generate plots to illustrate conclusions and support their analysis.