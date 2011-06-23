require 'rubygems'
require 'hoe'

Hoe.plugin :git, :doofus

Hoe.spec 'rets' do
  developer 'Estately, Inc. Open Source', 'opensource@estately.com'
  developer 'Ben Bleything',              'ben@bleything.net'

  extra_deps << [ "net-http-persistent", "~> 1.7" ]
  extra_deps << [ "nokogiri",            "~> 1.4.4" ]

  extra_dev_deps << [ "mocha", "~> 0.9.12" ]

  ### Use markdown for changelog and readme
  self.history_file = 'CHANGELOG.md'
  self.readme_file  = 'README.md'
end
