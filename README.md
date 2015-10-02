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
