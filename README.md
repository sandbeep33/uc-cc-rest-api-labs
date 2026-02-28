##GitHub Repository Structure — “uc-cc-rest-api-labs

uc-cc-rest-api-labs/
│
├── README.md
├── LICENSE
├── .gitignore
│
├── labs/
│   ├── lab01_rest_concepts/
│   │   ├── instructions.md
│   │   ├── exercises.md
│   │   └── solutions.md
│   │
│   ├── lab02_first_api_call/
│   │   ├── instructions.md
│   │   ├── sample_output.json
│   │   └── solutions/
│   │       └── first_api_call.py
│   │
│   ├── lab03_json_parsing/
│   │   ├── instructions.md
│   │   ├── sample_response.json
│   │   └── solutions/
│   │       └── json_parsing.py
│   │
│   ├── lab04_webex_api/
│   │   ├── instructions.md
│   │   ├── sample_requests/
│   │   │   ├── get_me.http
│   │   │   └── create_user.json
│   │   └── solutions/
│   │       └── webex_get_me.py
│   │
│   ├── lab05_zoom_api/
│   │   ├── instructions.md
│   │   ├── sample_requests/
│   │   │   ├── create_meeting.json
│   │   │   └── oauth_example.http
│   │   └── solutions/
│   │       └── zoom_create_meeting.py
│   │
│   ├── lab06_pagination/
│   │   ├── instructions.md
│   │   ├── sample_paginated_response.json
│   │   └── solutions/
│   │       └── pagination_loop.py
│   │
│   ├── lab07_error_handling/
│   │   ├── instructions.md
│   │   └── solutions/
│   │       └── error_handling_examples.py
│   │
│   ├── lab08_xml_parsing/
│   │   ├── instructions.md
│   │   ├── sample_cucm_response.xml
│   │   └── solutions/
│   │       └── xml_parsing.py
│   │
│   ├── lab09_async_api_calls/
│   │   ├── instructions.md
│   │   └── solutions/
│   │       └── async_parallel_calls.py
│   │
│   ├── lab10_nice_api/
│   │   ├── instructions.md
│   │   ├── sample_requests/
│   │   │   ├── update_skill.json
│   │   │   └── reporting_example.json
│   │   └── solutions/
│   │       └── nice_update_skill.py
│   │
│   └── final_project/
│       ├── instructions.md
│       ├── architecture_diagram.png
│       ├── sample_logs/
│       │   ├── webex.log
│       │   ├── zoom.log
│       │   └── nice.log
│       └── src/
│           ├── main.py
│           ├── webex_module.py
│           ├── zoom_module.py
│           ├── nice_module.py
│           ├── utils/
│           │   ├── auth.py
│           │   ├── pagination.py
│           │   ├── xml_parser.py
│           │   └── json_parser.py
│           └── config/
│               └── settings_template.json
│
├── docs/
│   ├── lab_workbook.pdf
│   ├── rest_cheat_sheet.pdf
│   ├── api_reference_notes.md
│   └── troubleshooting_guide.md
│
└── assets/
    ├── diagrams/
    │   ├── rest_flow.png
    │   ├── oauth_flow.png
    │   └── async_architecture.png
    └── screenshots/
        ├── postman_example.png
        ├── webex_token.png
        └── zoom_oauth_setup.png