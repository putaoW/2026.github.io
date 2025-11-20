source "https://rubygems.org"

# 核心依赖：让 Bundler 自动解析兼容版本
gem "jekyll", "4.4.1"                # 固定 Jekyll 版本
gem "jekyll-sass-converter", "3.1.0" # 固定转换器版本（它会自动要求 sass-embedded ~>1.75）
#  删除手动指定的 sass-embedded 版本，由 jekyll-sass-converter 自动关联

# 可选插件（根据需求保留/删除）
gem "jekyll-paginate", "~> 1.1"
gem "jekyll-feed", "~> 0.17.0"
gem "jekyll-seo-tag", "~> 2.8.0"

# 开发环境依赖
group :development do
  gem "jekyll-serve"
end
