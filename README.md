## LogogramNLP

This is the code and data repository for our paper: 

```
@article{chen2024logogramNLP,
  author    = {Danlu Chen, Freda Shi, Aditi Agarwal, Jacobo Myerston, Taylor Berg-Krikpatrick},
  title     = {LogogramNLP: Comparing Visual and Textual Representations of Ancient Logographic Writing Systems for NLP},
  journal   = {ACL},
  year      = {2024},
}
```

### Data for different tasks

The data used in the benchmark is as below:


#### Machine Translation

- **AKK**: The train/test/valid data is from [Akkademia](https://github.com/DigitalPasts/Akkademia/tree/master/NMT_input).
- **ZHO**: under the folder `data/CHO/translation`
- **EGY**: under the folder `data/EGY/translation`


#### Classification

- **AKK**:  obtained from [CuneiML](https://github.com/taineleau/CuneiML)
- **LNA**:  under the folder `data/LNA/classification`
- **ZHO**: under the folder `data/ZHO/classification`
- **EGY**: under the folder `data/EGY/classification`


#### Dependency parsing

- **AKK-MCONG**: obtained from [here](https://github.com/UniversalDependencies/UD_Akkadian-MCONG/tree/dev)


#### OCR

- **ZHO**: under the folder `data/EGY/OCR`
- **LNA**: under the folder `data/EGY/LNA`


### Code

