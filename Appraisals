%w(6.1 7.0 7.1 7.2).each do |version|
  appraise "rails-#{version.gsub(/\./, "-")}" do
    gem "rails", "~> #{version}.0"
  end
end

appraise "rails-8-0" do
  gem "rails", "~> 8.0.0"
  ruby ">= 3.2.0"
end
