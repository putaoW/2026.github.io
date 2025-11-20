source "https://rubygems.org"

# 核心依赖（与配置文件中 Ruby 3.3.5 兼容）
gem "jekyll", "4.4.1"                # 你的 Jekyll 版本
gem "jekyll-sass-converter", "3.1.0" # 配合 Jekyll 4.4.1 的 sass 转换器
gem "sass-embedded", "~> 1.54.0"     # 显式指定 sass-embedded 版本（避免自动升级冲突）

# 可选：常用插件（根据你的需求添加/删除）
gem "jekyll-paginate", "~> 1.1"      # 分页功能
gem "jekyll-feed", "~> 0.17.0"       # RSS 订阅功能
gem "jekyll-seo-tag", "~> 2.8.0"     # SEO 优化（自动生成 meta 标签）

# 开发环境依赖（本地调试用，部署时不加载）
group :development do
  gem "jekyll-serve"  # 本地启动服务（bundle exec jekyll serve）
end
