public:: true
tags:: 
exclude-from-graph-view:: true

- # 语言学习 lang
- {{query (page-property :tags "#🗺️lang")}}
  query-properties:: [:page :tags :exclude-from-graph-view :created-at]
- # 语言知识树
-
- {{query (page-property :tags "#🌲langtree")}}