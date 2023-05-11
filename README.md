# What makes an asshole character? What makes an asshole narrator?

This is the repository for our paper [Author as Character and Narrator: Deconstructing Personal Narratives from the r/AmITheAsshole Reddit Community](https://sjgiorgi.github.io/publications/giorgi2023author.pdf)


<img src="https://raw.githubusercontent.com/sjgiorgi/moral_judgements_in_aita/master/assets/aita_flow_diagram.png" width="100">



## Data

All data used in the paper is located in the `data/` folder. 

The file `narrator_and_character_features.csv` contains the following columns:

* `message_id`: unique identifier for the Reddit submission. This can be used to merge the features with the Reddit post text via the Reddit API.
* `aitah_binary`: binary outome 1 for "You're the asshole" and 0 for "You're NOT the asshole"

Author as Character features:

* `character__op_age`
* `character__op_gender`
* `character__op_age_missing`
* `character__op_gender_missing`
* `character__other_character_age`
* `character__other_character_gender`
* `character__op_agency`
* `character__op_power`
* `character__sentiment_arc`
* `character__chain_of_events`


Author as Narrator features:

* `narrator__first_person_singular`
* `narrator__first_person_plural`
* `narrator__third_person_singular`
* `narrator__third_person_plural`
* `narrator__first_third_person_ratio`
* `narrator__positive_sent`
* `narrator__negative_sent`
* `narrator__emotions_anger`
* `narrator__emotions_anticipation`
* `narrator__emotions_disgust`
* `narrator__emotions_fear`
* `narrator__emotions_joy`
* `narrator__emotions_sadness`
* `narrator__emotions_surprise`
* `narrator__emotions_trust`
* `narrator__dominant_tone`
* `narrator__concreteness`
* `narrator__familiarity`

## Citation

Please cite the following paper if you use this data:

```
@article{giorgi2023author,
  title={Author as Character and Narrator: Deconstructing Personal Narratives from the r/AmITheAsshole Reddit Community},
  author={Giorgi, Salvatore and Zhao, Ke and Feng, Alexander H and Martin, Lara J},
  journal={Proceedings of the International AAAI Conference on Web and Social Media},
  year={2023}
}

```

