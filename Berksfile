# -*- mode: ruby -*-
source "https://supermarket.getchef.com"

metadata

cookbook "python"
cookbook "git"
cookbook "build-essential"
cookbook "runit", '=1.5.10'

group :integration do
  cookbook "apt"
  cookbook "yum"
  cookbook "minitest-handler"
  cookbook "diamond_test", path: "test/cookbooks/diamond_test"
end
