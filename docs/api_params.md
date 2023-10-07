Here are all params that are usable via the new API approach, i.e., 
https://api.m2c2kit.com/m2c2kit/nt/index.html?activity_name=symbol-search&study_id=jonquerydemo&api_key=a0ecbfb5-7806-4a68-aa7c-3ce21b1066f9&number_of_trials=1|int&participant_id=None&session_id=05222d55-bc87-4c30-b756-c70ac9e62955&admin_type=missing

The key point is that parameters need to be spelled exactly as listed on the page below, and types need to be passed with a pipe seperator. For example, if I wanted 1 trial I would specify the URL param as: `number_of_trials=1|int`

https://m2c2-project.github.io/m2c2kit/docs/schemas/grid-memory
https://m2c2-project.github.io/m2c2kit/docs/schemas/color-dots
https://m2c2-project.github.io/m2c2kit/docs/schemas/color-shapes
https://m2c2-project.github.io/m2c2kit/docs/schemas/symbol-search

Aside from task params, other params are:
activity_name: symbol-search, grid-memory, color-shapes, color-dots
admin_type: qualtrics, metricwire
study_id: a study identifier (name)
session_id: a session identifier
participant_id: a participant identifier
api_key: a valid API key
group: a group indicator (str)
wave: a wave indicator (str)