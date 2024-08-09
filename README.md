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

---

#### Languages and writing systems

We includes four languages with different writing systems in our benchmark. We plan to include more languages if more data is available.

##### Linear A (undeciphered)

Linear A (1800–1450 BC) is an undeciphered language used by the Minoan at Crete and is believed to be not related to ancient Greek. Scholars have differentiated the glyphs and carefully hand-copied them into linearts. 

##### Akkadian (Cuneiform)

Akkadian, the language of ancient Mesopotamia, was recorded using cuneiform script, one of the earliest systems of writing. Cuneiform was used to inscribe a wide range of texts, from administrative records to epic literature, on clay tablets. We collected over 40,000 such tablets.

##### Ancient Egyptian (Hieroglyph)

Ancient Egyptian hieroglyphs represent one of the most iconic and enduring writing systems in human history, used for over three millennia in monumental inscriptions, religious texts, and administrative documents. 

##### Old Chinese (Bamboo script)

 The Bamboo script recorded the archaic time of Ancient Chinese (a.k.a. Old Chinese). We collected 13,770 pieces of bamboo slips from Kaom, which come with the photograph of each line of the text. The Baoshan collection covers three genres: Wen- shu (Document), Zhanbu (Divine), and Book. The Guodian collection contains parallel data translated into modern Chinese. The vocabulary size is 1,303. Notably, about 40% of the characters do not have a Unicode codepoint and are, therefore, represented as place-holder triangles or circles. 

---

### WIP: TODO

We are working on final cleanup of the datasets in the benchmark. 

- [x] data release and langauges description
- [ ] dataloader code
- [ ] notebook to visualize data
- [ ] training / inference code

---

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

----

### Code

WIP