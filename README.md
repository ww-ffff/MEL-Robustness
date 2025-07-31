# On Evaluating the Adversarial Robustness of Foundation Models for Multimodal Entity Linking

## Code

We use attacks implemented from [torchattack](https://github.com/Harry24k/adversarial-attacks-pytorch). 

We use two parameter settings: strong and normal. 

Default parameters can be found in attacks/config.yaml.


## Dataset 

### Get the Data

- The annotated data: [here](https://pan.baidu.com/s/1qPXquM12U_A3ebab6irdng?pwd=MELs)


### Dataset Format

- ADV-MEL
  - PGD-normal
    - $M^3EL$
      - attack sample.png
      - attack sample.pt
    - Richpedia_MEL
    - Wikidata_MEL
    - WikiDiverse
    - WikiPerson
  - PGD-strong
  - APGD-normal
  - APGD-strong
  - CW-normal
  - CW-strong
