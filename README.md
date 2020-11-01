# Exercise-Template

![Status](https://img.shields.io/badge/status-release-green) ![GitHub top language](https://img.shields.io/github/languages/top/jfklorenz/Curriculum-Vitae) ![GitHub](https://img.shields.io/github/license/jfklorenz/Curriculum-Vitae)

*LaTeX* template *documentclass* for university exercises.

The template can be used via `\documentclass[parameter]{exercise}` and automatically uses certain packages and defines new commands.

Parameter | Explanation | Example
--- | --- | ---
name | your name | `Max\ Mustermann`
mtr | student ID | 123456
fach | subject | `Lineare Algebra`
nr | exercise number | 4
mp | maximum points (exercise) | 20

The documentclass also provides a new *environment* for tasks via `\begin{aufgabe}{theme}{mp}{text}`.

Parameter | Explanation | Example
--- | --- | ---
theme | theme of the task | `Lineare\ Gleichungssysteme`
mp | maximum points (task) | 8
text | task content | `\lipsum`

All of the above can be seen in the example file called `example.tex`. 

The package is designed for *german* exercises but can easily be adapted to any language.
