source "https://rubygems.org"

# 核心依赖：仅保留必要配置，避免版本冲突
gem "jekyll", "4.4.1"                # 固定你的 Jekyll 版本
gem "jekyll-sass-converter", "3.1.0" # 固定转换器版本（自动关联 sass-embedded ~>1.75）

# 可选插件（根据你的实际需求保留/删除，无冲突）
gem "jekyll-paginate", "~> 1.1"
gem "jekyll-feed", "~> 0.17.0"
gem "jekyll-seo-tag", "~> 2.8.0"

# 开发环境依赖（本地调试用，部署时不加载）
group :development do
  gem "jekyll-serve"
end
