### What is Dharma.

[Dharma](https://github.com/MozillaSecurity/dharma) is a grammar-based test generator and fuzzing tool. It is based on grammars files (which are templates for the creation of scripts written in C, Python, JavaScript, etc using Dharma's API).

In this repository you will find documentation of this tool and documented grammars for several APIs and program languages written to be used with Dharma.

<br>

### Install and running Dharma.

On a Linux enviroment we can install Dharma through the following command:

```bash
pip install dharma
dharma --help
```

Once we have the tool installed, we can run the following command to run Dharma with a grammar file in order to produce several programs through the grammar template file.

```bash
dharma -grammars <path/to/file.dg> -count <numberofiles> -format <extension> -seed 1337 -storage <output_folder>
```

<br>

### Documentation about Dharma.

Information about use and examples are available on the following [link](https://qv1ntv5.github.io/2024-03-22-Dharma_Tutorial/)

