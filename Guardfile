# A sample Guardfile
# More info at https://github.com/guard/guard#readme

guard 'compass' do
  watch %r{sass/.+(\.s[ac]ss)}
end

guard 'coffeescript', :output => 'js' do
  watch(%r{coffeescripts/(.+\.coffee)})
end

guard 'livereload', :configuration_file => 'config.rb' do
  watch(%r{js/.+\.js})
  watch(%r{.+\.php})
  watch(%r{.+\.css})
end
