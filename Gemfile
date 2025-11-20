source "https://rubygems.org"

# 核心依赖（解决版本冲突 + 缺失插件）
gem "jekyll", "4.4.1"
gem "jekyll-sass-converter", "3.1.0"
gem "jekyll-sitemap", "~> 1.4.0"  # 添加缺失的 sitemap 插件，版本兼容 Jekyll 4.4.1

# 可选插件（保留之前的，无冲突）
gem "jekyll-paginate", "~> 1.1"
gem "jekyll-feed", "~> 0.17.0"
gem "jekyll-seo-tag", "~> 2.8.0"

# 开发环境依赖
group :development do
  gem "jekyll-serve"
end

# 解决 Ruby 3.5.0 警告（可选，消除 logger 提示）
gem "logger", "~> 1.5.3"
