Thanks for downloading this theme!

Theme Name: TheEvent
Theme URL: https://bootstrapmade.com/theevent-conference-event-bootstrap-template/
Author: BootstrapMade.com
Author URL: https://bootstrapmade.com



fetch("http:// localhost:4000/graphql",{
    method:"POST",
    headers:{
        "Content-Type":"application/json",
        "Accept":"application/json",
    },
    body:JSON.stringify({
        query
    })
}).then(response=>{
    return response.json();
}).then(data=>{
    console.log(data);
});