# novel-plus-test
对开源项目小说精品屋novel-plus进行功能和接口自动化测试

预期目录结构：
novel-plus-test/
├── 01_需求分析/
│   └── 业务逻辑梳理.md
├── 02_测试计划/
│   └── 测试计划_v1.0.md
├── 03_测试点/
│   └── 测试点_XMind.xmind
├── 04_测试用例/
│   ├── 功能测试用例.xlsx
│   └── 接口测试用例.xlsx（或Postman Collection）
├── 05_脚本/
│   ├── postman/
│   │   ├── novel_plus_collection.json
│   │   └── environment.json
│   ├── jmeter/
│   |   ├── novel_load_test.jmx
│   |   └── 性能测试报告.md
│   ├── selenium_ui/
│   │   ├── pages/               # Page Object 页面类
│   │   ├── tests/               # pytest 测试用例
│   │   ├── conftest.py
│   │   ├── requirements.txt
│   │   └── allure-results/      # 测试报告
│   └── api_pytest/              # 如果你也想用pytest做接口自动化
│       ├── test_api.py
│       └── utils/
├── 06_测试数据/
│   └── 预置数据.sql
├── 07_缺陷报告/
│   └── bug清单.md（可从禅道导出）
├── 08_测试报告/
│   └── 测试总结报告.md
└── README.md               # 项目说明，包含如何运行接口脚本
