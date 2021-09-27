# aligned_qa

#### [build tydiqa-baseline](https://github.com/google-research-datasets/tydiqa/tree/master/baseline)

#### [Dataset](https://drive.google.com/drive/folders/1J--Qs8gbWwk1saAqozkXTZddzjIEfqvc?usp=sharing)

| Dataset Description | File\Folder name |
|-------------- | -----|
|`train_data`||
|TyDi-QA-mono | tydiqa-v1.0-train-discard-dev.jsonl.gz|
|TyDi-QA-aug (q:english, c: other) | tydiqa-v1.0-train-discard-dev-langtoeng-google.jsonl.gz |
|TyDi-QA-aug (q:other, c: english) | tydiqa-v1.0-train-discard-dev-engtolang-google.jsonl.gz |
|`dev_data`|
|TyDi-QA-mono | tydiqa-v1.0-custom-dev.jsonl.gz|
|TyDi-QA-aug (q:english, c: other, google_mt) | tydiqa-v1.0-custom-dev-langtoeng.jsonl.gz |
|TyDi-QA-aug (q:other, c: english, google_mt) | tydiqa-v1.0-custom-dev-engtolang.jsonl.gz |
|`test_data`|
|TyDi-QA-mono | tydiqa-v1.0-custom-test.jsonl.gz|
|TyDi-QA-aug (q:english, c: other) | tydiqa-v1.0-custom-dev-langtoeng.jsonl.gz |
|TyDi-QA-aug (q:other, c: english) | tydiqa-v1.0-custom-dev-engtolang.jsonl.gz |
|`dev/test_human_translations (to english)`|
|TyDi-QA-aug (q:english, c: bangla, dev, google_asr)| tydiqa-v1.0-custom-dev-ben-en-US.jsonl.gz|
|TyDi-QA-aug (q:english, c: bangla, test, google_asr)| tydiqa-v1.0-custom-test-ben-en-US.jsonl.gz|
|TyDi-QA-aug (q:english, c: bangla, test, human_transcription)| tydiqa-v1.0-custom-test-ben-english-gold.jsonl.gz|
|TyDi-QA-aug (q:english, c: swahili, test, google_asr)| tydiqa-v1.0-custom-test-swa-en-US.jsonl.gz|
|`question_translations_google_mt`|
|Train data question translations (to english, from english)| question_translations_google_mt\trans_train_questions\\*|
|Dev data question translations (to english, from english)| question_translations_google_mt\trans_dev_questions\\*|
|Test data question translations (to english, from english)| question_translations_google_mt\trans_test_questions\\*|

## Citation
If you find this codebase is useful or use the data in your work, please cite our paper. [Investigating Post-pretraining Representation Alignment for Cross-Lingual Question Answering](https://arxiv.org/abs/2109.12028). You can use the following BibTeX entry
~~~
@misc{faisal2021investigating,
      title={Investigating Post-pretraining Representation Alignment for Cross-Lingual Question Answering}, 
      author={Fahim Faisal and Antonios Anastasopoulos},
      year={2021},
      eprint={2109.12028},
      archivePrefix={arXiv},
      primaryClass={cs.CL}
}
~~~

We built our augmented dataset and baselines on top of TydiQA. Kindly also make sure to cite the original TyDi QA paper,
~~~
@article{tydiqa,
title   = {TyDi QA: A Benchmark for Information-Seeking Question Answering in Typologically Diverse Languages},
author  = {Jonathan H. Clark and Eunsol Choi and Michael Collins and Dan Garrette and Tom Kwiatkowski and Vitaly Nikolaev and Jennimaria Palomaki}
journal = {TACL},
year    = {2020}
}
