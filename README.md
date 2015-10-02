# rail

### Router
    default root page<br/>
    root :to => "demo#index"


### View
    render('demo/hello')
    redirect_to(
        :controller=>'demo',
        :action=>'index'
    ) 
    redirect_to("http://www.yahoo.com.tw")
    
### DB
    rake db:schema:dump RAILS_ENV=production
    
##### Table column Type    
    binary , boolean , date , datetime , decimal , float , integer , string , text , time
    :limit => size
    :default => value
    :null => true/false
    :precision => number
    :scale => number
    
##### Running Migrations
    rake db:migrate
    rake db:migrate VERSION=0
    rake db:migrate VERSION=201312311235959
    rake db:migrate:status
    rake db:up VERSION=20132222222
    rake db:down VERSION=20132222222
    rake db:redo VERSION=20132222222
