# Flash-Chat
Following along [The App Brewery](https://www.appbrewery.co) 📱 Flash-Chat Project.

A chat app using Firebase real-time database.



## Podfile Configuration
```
post_install do |installer|
    installer.pods_project.targets.each do |target|
        target.build_configurations.each do |config|
            config.build_settings['CLANG_WARN_DOCUMENTATION_COMMENTS'] = 'NO'
        end
    end
end
```

## Finished App
![Finished App](https://github.com/londonappbrewery/Images/blob/master/Flash%20Chat.gif)


