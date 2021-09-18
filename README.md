# aligned_qa

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