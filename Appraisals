%w(6.1 7.0 7.1 7.2 8.0).each do |version|
  appraise "rails-#{version.gsub(/\./, "-")}" do
    gem "rails", "~> #{version}.0"
    ruby "3.3" if version == "8.0"
  end
end
