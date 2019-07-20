..  Licensed to the Apache Software Foundation (ASF) under one
    or more contributor license agreements.  See the NOTICE file
    distributed with this work for additional information
    regarding copyright ownership.  The ASF licenses this file
    to you under the Apache License, Version 2.0 (the
    "License"); you may not use this file except in compliance
    with the License.  You may obtain a copy of the License at

..    http://www.apache.org/licenses/LICENSE-2.0

..  Unless required by applicable law or agreed to in writing,
    software distributed under the License is distributed on an
    "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY
    KIND, either express or implied.  See the License for the
    specific language governing permissions and limitations
    under the License.

|apache_img| |superset_img|

.. |apache_img| image:: images/apache_feather.png
   :width: 7%
   :target: http://www.apache.org/
   :alt: The Apache Software Foundation

.. |superset_img| image:: images/s.png
   :width: 25%

Apache Superset (incubating)
''''''''''''''''''''''''''''

Apache Superset （孵化中）是一个现代化，企业级商业智能的web应用。


----------------

.. important::

    **Disclaimer**: Apache Superset is an effort undergoing incubation at The
    Apache Software Foundation (ASF), sponsored by the Apache Incubator.
    Incubation is required of all newly accepted projects until a further
    review indicates that the infrastructure, communications, and
    decision making process have stabilized in a manner consistent with
    other successful ASF projects. While incubation status is not
    necessarily a reflection of the completeness or stability of
    the code, it does indicate that the project has yet to be fully
    endorsed by the ASF.

.. note:: Apache Superset, Superset, Apache, the Apache feather logo, and
    the Apache Superset project logo are either registered trademarks or
    trademarks of The Apache Software Foundation in the United States
    and other countries.

Superset 资源
==================
- `Superset's Github <https://github.com/apache/incubator-superset>`_, 注意
 `我们使用 Github for 跟踪问题 <https://github.com/apache/incubator-superset/issues>`_
- Superset's
  `贡献指南 <https://github.com/apache/incubator-superset/blob/master/CONTRIBUTING.md>`_
  and
  `行为准则 <https://github.com/apache/incubator-superset/blob/master/CODE_OF_CONDUCT.md>`_
  Github.
- 我们的 `邮件列表归档 <https://lists.apache.org/list.html?dev@superset.apache.org>`_.
  订阅发送邮件到 ``dev-subscribe@superset.apache.org``
- `加入Slack <https://join.slack.com/t/apache-superset/shared_invite/enQtNDMxMDY5NjM4MDU0LTc2Y2QwYjE4NGYwNzQyZWUwYTExZTdiZDMzMWQwZjc2YmJmM2QyMDkwMGVjZTA4N2I2MzUxZTk2YmE5MWRhZWE>`_

Apache软件基金会资源
====================================
- `Apache软件基金会网站 <http://www.apache.org>`_
- `最近活动 <http://www.apache.org/events/current-event>`_
- `License <https://www.apache.org/licenses/>`_
- `赞助者名单 <https://www.apache.org/foundation/thanks.html>`_
- `赞助 Apache! <http://www.apache.org/foundation/sponsorship.html>`_

概括
========

特性
--------

- 丰富的数据可视化
- 易用的界面用于探索和可视化数据
- 创建和分享仪表盘
- 整合了主要的企业级认证方式 (database, OpenID, LDAP, OAuth & REMOTE_USER through
  Flask AppBuilder)
- 可扩展高粒度的权限模型，允许负责的规则对功能和数据进行控制
- 简单的语义定义数据源，用户可以控制哪些字段显示在下拉列表中，哪些聚合和指标对用户可用。
- 通过 SQLAlchemy 整合大部分的关系型数据的SQL方言
- 深度整合 Druid.io

支持的数据库
------------

下面是支持的关系型数据库列表:

- `Amazon Athena <https://aws.amazon.com/athena/>`_
- `Amazon Redshift <https://aws.amazon.com/redshift/>`_
- `Apache Drill <https://drill.apache.org/>`_
- `Apache Druid <http://druid.io/>`_
- `Apache Hive <https://hive.apache.org/>`_
- `Apache Impala <https://impala.apache.org/>`_
- `Apache Kylin <http://kylin.apache.org/>`_
- `Apache Pinot <https://pinot.incubator.apache.org/>`_
- `Apache Spark SQL <https://spark.apache.org/sql/>`_
- `BigQuery <https://cloud.google.com/bigquery/>`_
- `ClickHouse <https://clickhouse.yandex/>`_
- `Google Sheets <https://www.google.com/sheets/about/>`_
- `Greenplum <https://greenplum.org/>`_
- `IBM Db2 <https://www.ibm.com/analytics/db2/>`_
- `MySQL <https://www.mysql.com/>`_
- `Oracle <https://www.oracle.com/database/>`_
- `PostgreSQL <https://www.postgresql.org/>`_
- `Presto <http://prestodb.github.io/>`_
- `Snowflake <https://www.snowflake.com/>`_
- `SQLite <https://www.sqlite.org/>`_
- `SQL Server <https://www.microsoft.com/en-us/sql-server/>`_
- `Teradata <https://www.teradata.com/>`_
- `Vertica <https://www.vertica.com/>`_

其他SQLAclchemy支持的数据库访问

截屏
-----------

.. image:: images/screenshots/bank_dash.png

------

.. image:: images/screenshots/explore.png

------

.. image:: images/screenshots/sqllab.png

------

.. image:: images/screenshots/deckgl_dash.png

------


目录
--------

.. toctree::
    :maxdepth: 2

    installation
    tutorial
    security
    sqllab
    gallery
    druid
    misc
    faq


Indices and tables
------------------

* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`
