---
title: Trucks Repair | Web oficial
layout: "main.njk"
---
            <section>

                <div class="p-5 mb-4 bg-dark border">
                    <div class="container-fluid p-5">
                        <h1 class="display-5 fw-bold">hero main</h1>
                        <p class="col-md-8 fs-4">
                            Using a series of utilities, you can create this jumbotron, just
                            like the one in previous versions of Bootstrap. Check out the
                            examples below for how you can remix and restyle it to your liking.
                        </p>
                        <button class="btn btn-primary btn-lg" type="button">
                            cta btn
                        </button>
                    </div>
                </div>
        
            </section>

            <section class="container">


                <div class="row text-center">

                    <div class="col-lg border">
                        <div class="card bg-dark text-white"><h3>servicio 1</h3></div>        
                    </div>
                    <div class="col-lg border">
                        <div class="card bg-dark text-white"><h3>servicio 2</h3></div>
                    </div>
                    <div class="col-lg border">
                        <div class="card bg-dark text-white"><h3>servicio 3</h3></div>                            
                    </div>

                </div>
                
            </section>            


            <section>

                <div class="p-5 mb-4 bg-dark border">
                    <div class="container-fluid text-center p-5">
                        <h1 class="display-5 fw-bold">article</h1>
                        <p class="fs-4">
                            Using a series of utilities, you can create this jumbotron, just
                            like the one in previous versions of Bootstrap. Check out the
                            examples below for how you can remix and restyle it to your liking.
                        </p>
                        <button class="btn btn-primary btn-lg" type="button">
                            cta btn
                        </button>
                    </div>
                </div>
        
            </section>            



            <section class="container text-center border">

                <h1>articles </h1>

                <h2>welcome to my first page</h2>


                    {% for post in collections.blog %}

                    - [{{ post.data.title }}]({{post.url}})

                    {% endfor %}               



            </section>


            
