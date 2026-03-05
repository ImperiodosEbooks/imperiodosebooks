<!DOCTYPE html><html lang="pt-br">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Império dos Ebooks</title>
<style>
body{margin:0;font-family:Arial;background:#f5f5f5}
header{background:#000;color:#fff;padding:15px;text-align:center}
.container{padding:20px}
.products{display:grid;grid-template-columns:repeat(auto-fit,minmax(220px,1fr));gap:20px}
.card{background:#fff;padding:12px;border-radius:12px;box-shadow:0 4px 10px rgba(0,0,0,.1)}
img{width:100%;border-radius:10px}
button{background:#000;color:#fff;border:none;padding:10px;margin-top:8px;width:100%;cursor:pointer;border-radius:8px}
input,textarea{width:100%;margin:5px 0;padding:8px}
#admin{display:none;background:#fff;padding:20px;border-radius:12px;margin-bottom:20px}
.top-bar{display:flex;justify-content:space-between;align-items:center}
.search{padding:8px;width:200px}
.delete{background:red}
</style>
</head>
<body><header>
  <h1>Império dos Ebooks</h1>
</header><div class="container"><div class="top-bar">
  <button onclick="login()">Área do Admin</button>
  <input class="search" placeholder="Buscar produto..." oninput="buscar(this.value)">
</div><div id="admin">
  <h2>Adicionar Produto</h2>
  <input id="titulo" placeholder="Título">
  <textarea id="descricao" placeholder="Descrição"></textarea>
  <input id="imagem" placeholder="URL da imagem">
  <input id="preco" type="number" placeholder="Preço">
  <button onclick="addProduct()">Salvar Produto</button>
</div><h2>Produtos</h2>
<div class="products" id="lista"></div></div><script>
let produtos = JSON.parse(localStorage.getItem("produtos")) || [];
let adminLogado = false;

function salvar(){
  localStorage.setItem("produtos", JSON.stringify(produtos));
}

function login(){
  let email = prompt("Email:");
  let senha = prompt("Senha:");

  if(email === "lucasminecraft1107@gmail.com" && senha === "1234"){
    adminLogado = true;
    document.getElementById("admin").style.display = "block";
  } else {
    alert("Acesso negado");
  }
}

function addProduct(){
  let produto = {
    id: Date.now(),
    titulo: titulo.value,
    descricao: descricao.value,
    imagem: imagem.value,
    preco: preco.value
  };

  produtos.push(produto);
  salvar();
  render();
}

function deletar(id){
  produtos = produtos.filter(p => p.id !== id);
  salvar();
  render();
}

function comprar(produto){
  let msg = `Olá, quero comprar: ${produto.titulo} - R$ ${produto.preco}`;
  window.open(`https://wa.me/5532999999999?text=${encodeURIComponent(msg)}`);
}

function render(listaFiltrada = produtos){
  let lista = document.getElementById("lista");
  lista.innerHTML = "";

  listaFiltrada.forEach(p => {
    lista.innerHTML += `
      <div class="card">
        <img src="${p.imagem}">
        <h3>${p.titulo}</h3>
        <p>${p.descricao}</p>
        <strong>R$ ${p.preco}</strong>
        <button onclick='comprar(${JSON.stringify(p)})'>Comprar</button>
        ${adminLogado ? `<button class="delete" onclick="deletar(${p.id})">Excluir</button>` : ""}
      </div>
    `;
  });
}

function buscar(texto){
  let filtro = produtos.filter(p => p.titulo.toLowerCase().includes(texto.toLowerCase()));
  render(filtro);
}

render();
</script></body>
</html>
