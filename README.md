# JIPCAD-XML (WIP)

XML to [JIPCAD](https://jipcad.github.io/) `.nom` coversion/transpiler (hopefully) written in C!

this is just a personal project :D - feel free to contribute!

### Background

I've been using CAD since High School and have always been interested in cool ways to make geometry!

After spending months working with XML-based [GDML](https://indico.cern.ch/event/408139/contributions/979922/attachments/815913/1118019/GDML_CHEP06.pdf) (Geometry Description Markup Language), I created a close-source GDML builder in python, and realized how nice XML was in terms of storing, and reconstructing data in a human-readable format. It's just a shame GDML isn't that popular and has minimal documentation.

After learning about [JIPCAD](https://jipcad.github.io/) and the `.nom` format, I was really interested in working with it. This project is my attempt at creating a more readable way to create JIPCAD geometry w/ XML while learning more about XML schemas, JIPCAD, and C.

## Features

- Custom xml [schema](https://raw.githubusercontent.com/xa1on/JIPCAD-XML/refs/heads/main/schema/nome.xsd) for `.nomxml`

## WIP
- Finish schema
- Create example geometry in `.nomxml`
- `.nomxml` to `.nom` conversion
- `.nom` to `.nomxml` conversion
- Command Line Interface