

<a name="readme-top"></a>

<div align="center">
	<a href="https://pypi.org/project/MindsDB/" target="_blank"><img src="https://badge.fury.io/py/MindsDB.svg" alt="MindsDB Release"></a>
	<a href="https://www.python.org/downloads/" target="_blank"><img src="https://img.shields.io/badge/python-3.10.x%7C%203.11.x-brightgreen.svg" alt="Python supported"></a>
	<a href="https://ossrank.com/p/630"><img src="https://shields.io/endpoint?url=https://ossrank.com/shield/630"></a>
	<img alt="PyPI - Downloads" src="https://img.shields.io/pypi/dm/Mindsdb">
	<a href="https://hub.docker.com/u/mindsdb" target="_blank"><img src="https://img.shields.io/docker/pulls/mindsdb/mindsdb" alt="Docker pulls"></a>

  <br />
  <br />

  <a href="https://github.com/mindsdb/mindsdb">
    <img src="/docs/assets/mindsdb_logo.png" alt="MindsDB" width="300">
  </a>

  <p align="center">
    <br />
    <a href="https://www.mindsdb.com?utm_medium=community&utm_source=github&utm_campaign=mindsdb%20repo">Website</a>
    ·
    <a href="https://docs.mindsdb.com?utm_medium=community&utm_source=github&utm_campaign=mindsdb%20repo">Docs</a>
    ·
    <a href="https://mindsdb.com/contact">Contact us for a Demo</a>
    ·
    <a href="https://mindsdb.com/joincommunity?utm_medium=community&utm_source=github&utm_campaign=mindsdb%20repo">Community Slack</a>
  </p>
</div>

----------------------------------------


MindsDB enables humans, AI, agents, and applications to get highly accurate answers across sprawled and large scale data sources.

![image](https://github.com/user-attachments/assets/a796276a-2d3e-4aa2-9a52-25bf44cf32e7)


[MindsDB has an MCP server built in](https://docs.mindsdb.com/mcp/overview) that enables your MCP applications to connect, unify and respond to questions over large-scale federated data—spanning databases, data warehouses, and SaaS applications.
 
## Install MindsDB Server 

MindsDB is an open-source server that can be deployed anywhere - from your laptop to the cloud, and everywhere in between. And yes, you can customize it to your heart's content.

  * [Using Docker Desktop](https://docs.mindsdb.com/setup/self-hosted/docker-desktop). This is the fastest and recommended way to get started and have it all running.
  * [Using Docker](https://docs.mindsdb.com/setup/self-hosted/docker). This is also simple, but gives you more flexibility on how to further customize your server.
  * [Using PyPI](https://docs.mindsdb.com/contribute/install). This option enables you to contribute to MindsDB.

----------------------------------------

# Core Philosophy: Connect, Unify, Respond

MindsDB's architecture is built around three fundamental capabilities:

## [Connect](https://docs.mindsdb.com/integrations/data-overview) Your Data

You can connect to hundreds of enterprise [data sources (learn more)](https://docs.mindsdb.com/integrations/data-overview). These integrations allow MindsDB to access data wherever it resides, forming the foundation for all other capabilities.

## [Unify](https://docs.mindsdb.com/mindsdb_sql/overview) Your Data

Once connected, these data sources can be queried using a full SQL dialect, as if they were all part of a single database. MindsDB’s federated query engine translates your SQL queries and executes them on the appropriate connected data sources.

When working with many data sources, it’s important to prepare and unify your data before generating responses from it. MindsDB SQL offers virtual tables (views, knowledge bases, ml-models) to allow working with heterogeneous data as if it were unified in a single organized system.

* [**VIEWS**](https://docs.mindsdb.com/mindsdb_sql/sql/create/view) – Simplify data access by creating unified views across different sources (no-ETL).
* [**KNOWLEDGE BASES**](https://docs.mindsdb.com/mindsdb_sql/knowledge-bases) – Index and organize unstructured data for efficient retrieval.
* [**ML MODELS**](https://docs.mindsdb.com/mindsdb_sql/sql/create/model) – Apply AI/ML transformations to gain insights from your data.

Unification of data can be automated using JOBs

* [**JOBS**](https://docs.mindsdb.com/mindsdb_sql/sql/create/jobs) – Schedule synchronization and transformation tasks for real-time processing.


## [Respond](https://docs.mindsdb.com/mindsdb_sql/agents/agent) From Your Data

Chat with Your Data

* [**AGENTS**](https://docs.mindsdb.com/mindsdb_sql/agents/agent) – Configure built-in agents specialized in answering questions over your connected and unified data.
* [**MCP**](https://docs.mindsdb.com/mcp/overview) – Connect to MindsDB through the MCP (Model Context Protocol) for seamless interaction.

----------------------------------------

## 🤝 Contribute

Interested in contributing to MindsDB? Follow our [installation guide for development](https://docs.mindsdb.com/contribute/install?utm_medium=community&utm_source=github&utm_campaign=mindsdb%20repo).

You can find our [contribution guide here](https://docs.mindsdb.com/contribute/contribute?utm_medium=community&utm_source=github&utm_campaign=mindsdb%20repo).

We welcome suggestions! Feel free to open new issues with your ideas, and we’ll guide you.

This project adheres to a [Contributor Code of Conduct](https://github.com/mindsdb/mindsdb/blob/main/CODE_OF_CONDUCT.md). By participating, you agree to follow its terms.

Also, check out our [community rewards and programs](https://mindsdb.com/community?utm_medium=community&utm_source=github&utm_campaign=mindsdb%20repo).

## 🤍 Support

If you find a bug, please submit an [issue on GitHub](https://github.com/mindsdb/mindsdb/issues/new/choose).

Here’s how you can get community support:

* Ask a question in our [Slack Community](https://mindsdb.com/joincommunity?utm_medium=community&utm_source=github&utm_campaign=mindsdb%20repo).
* Join our [GitHub Discussions](https://github.com/mindsdb/mindsdb/discussions).
* Post on [Stack Overflow](https://stackoverflow.com/questions/tagged/mindsdb) with the MindsDB tag.

For commercial support, please [contact the MindsDB team](https://mindsdb.com/contact?utm_medium=community&utm_source=github&utm_campaign=mindsdb%20repo).

## 💚 Current Contributors

<a href="https://github.com/mindsdb/mindsdb/graphs/contributors">
  <img src="https://contributors-img.web.app/image?repo=mindsdb/mindsdb" />
</a>

Generated with [contributors-img](https://contributors-img.web.app).

## 🔔 Subscribe for Updates

Join our [Slack community](https://mindsdb.com/joincommunity)


MindsDB Là Gì?
MindsDB là một nền tảng mã nguồn mở giúp bạn (con người, AI, các phần mềm,...) truy vấn, phân tích và lấy câu trả lời thông minh từ nhiều nguồn dữ liệu lớn khác nhau — ví dụ như database, data warehouse (kho dữ liệu), ứng dụng SaaS (dịch vụ điện toán đám mây kiểu như Google Drive, Salesforce,...).

Bạn có thể hiểu MindsDB như một “trợ lý AI” biết kết nối và tổng hợp dữ liệu từ nhiều nơi, rồi trả lời các câu hỏi phức tạp về dữ liệu đó cho bạn.

MindsDB Hoạt Động Như Thế Nào? (3 Bước Lớn)
1. Kết Nối Dữ Liệu (Connect)
MindsDB có thể kết nối tới hàng trăm nguồn dữ liệu khác nhau (database, file lưu trữ, SaaS...).

Bạn chỉ cần cấu hình thông tin kết nối, MindsDB sẽ “nhìn thấy” và truy cập được dữ liệu ở đó.

2. Hợp Nhất Dữ Liệu (Unify)
Khi đã kết nối nhiều nguồn, MindsDB cho phép bạn truy vấn dữ liệu giống như đang làm việc với một cơ sở dữ liệu lớn duy nhất, dù dữ liệu thật ra nằm rải rác nhiều nơi.

Bạn sử dụng ngôn ngữ SQL (ngôn ngữ truy vấn quen thuộc với dân IT/phân tích dữ liệu) để lấy dữ liệu, xử lý, tổng hợp,...

Có nhiều công cụ như:

VIEW: tạo bảng ảo hợp nhất từ nhiều nguồn.

KNOWLEDGE BASE: tổ chức dữ liệu chưa có cấu trúc.

ML MODEL: áp dụng AI/Machine Learning ngay trên dữ liệu đó.

JOB: tự động hóa các công việc đồng bộ, xử lý dữ liệu theo lịch.

3. Trả Lời Thông Minh (Respond)
MindsDB cho phép bạn giao tiếp/chat với dữ liệu: hỏi gì, trả lời đó (kiểu ChatGPT, nhưng là với dữ liệu của bạn).

Bạn có thể cấu hình AGENT để trả lời tự động cho các câu hỏi về dữ liệu.

Ngoài ra, MindsDB hỗ trợ giao tiếp qua chuẩn MCP giúp ứng dụng khác dễ dàng tích hợp.

Lợi Ích Khi Sử Dụng MindsDB
Tự động hóa việc phân tích dữ liệu phức tạp, không cần copy-dán thủ công.

Kết nối, hợp nhất dữ liệu nhanh chóng từ nhiều nguồn mà không phải viết code chuyển đổi phức tạp.

Dễ mở rộng, tùy biến: là mã nguồn mở, bạn có thể cài trên máy cá nhân, server riêng, hoặc cloud.

Hỗ trợ AI/Machine Learning ngay trên dữ liệu thực tế (thay vì phải xuất ra ngoài rồi phân tích).

Cách Bắt Đầu Sử Dụng
Có 3 cách cài MindsDB:

Bằng Docker Desktop: Cách nhanh, dễ nhất cho người mới.

Bằng Docker thông thường: Dễ tùy chỉnh, hợp cho môi trường chuyên nghiệp.

Cài qua PyPI: Dành cho ai muốn đóng góp phát triển MindsDB.

Bạn nên thử Docker Desktop nếu mới bắt đầu.

Hỗ Trợ & Đóng Góp
Có thể tham gia cộng đồng Slack, GitHub Discussions, Stack Overflow để hỏi đáp.

Có thể đóng góp code, mở issues khi gặp bug, hoặc gửi ý tưởng mới.

Có chương trình phần thưởng cho người đóng góp tích cực.

Tóm Lại
MindsDB là một nền tảng giúp bạn dễ dàng kết nối, hợp nhất và phân tích dữ liệu từ nhiều nguồn khác nhau, đồng thời có thể hỏi đáp thông minh với dữ liệu đó, kể cả khi bạn không rành về lập trình hoặc Machine Learning.

Nếu bạn là người mới, hãy thử cài MindsDB bằng Docker Desktop, đọc thêm tài liệu hướng dẫn trên trang chủ MindsDB hoặc tài liệu docs.
