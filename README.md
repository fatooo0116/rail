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
