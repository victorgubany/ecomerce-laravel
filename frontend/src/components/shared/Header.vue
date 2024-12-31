    <template>
        <div class="container">
            <nav class="navbar navbar-expand-lg bg-body-tertiary">
                <div class="container-fluid">
                    <a class="navbar-brand" href="#">Navbar</a>
                    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNavAltMarkup" aria-controls="navbarNavAltMarkup" aria-expanded="false" aria-label="Toggle navigation">
                    <span class="navbar-toggler-icon"></span>
                    </button>
                    <div class="collapse navbar-collapse" id="navbarNavAltMarkup">
                    <div class="navbar-nav">
                        <a class="nav-link active" aria-current="page" href="#">Inicio</a>
                        <a class="nav-link" href="#">Produtos</a>
                        <a class="nav-link" href="#">Categorias</a>

                    </div>
                    
                    </div>
                    <div class="mx-2">
                        <form class="d-flex" role="search">
                            <input class="form-control me-2" type="search" placeholder="Digite um produto" aria-label="Search">
                            <button class="btn btn-outline-success" type="submit">Pesquisar</button>
                        </form>
                    </div>
                    <div class="mx-2">
                        <a class="nav-link" href="#">Entrar</a>
                    </div>
                </div>
            </nav> 
        </div>
 
  </template>
  
  <script>
    export default {
        name: "Header",
    };
  </script>
  

  