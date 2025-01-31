<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>bNM Drink</title>
    <!-- Ícones -->
    <link 
    rel="stylesheet" 
    href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.7.2/css/all.min.css" 
    integrity="sha512-Evv84Mr4kqVGRNSgIGL/F/aIDqQb7xQ2vcrdIwxfjThSH8CSR7PBEakCr51Ck+w+/U6swU2Im1vVX0SVk9ABhg==" 
    crossorigin="anonymous" 
    referrerpolicy="no-referrer" 
    />
    <!-- Estilos -->
    <link rel="stylesheet" href="css/styles.css">
</head>
<body>
    <div class="container">
        <div class="navbar-container">
            <nav>
                <a href="#">
                    <img src="img/logo.jpeg" alt="bNM Drink" class="logo" >
                </a>
                <ul class="navbar-items">
                    <li>
                        <a href="#">Home</a>
                    </li>
                    <li>
                        <a href="#">Preços</a>
                    </li>
                    <li>
                        <a href="#">Contato</a>
                    </li>
                    <li>
                        <a href="#" class="default-btn">Entrar</a>
                    </li>
                </ul>
            </nav>            
        </div>
        <main>
            <div class="main-banner">
                <h1>bNM Drink</h1>
                <p>Os melhores serviços para suas festas!</p>
            </div> 
            <section class="services-container">
                <ul>
                    <li>    
                        <i class="fas fa-shield-alt"></i>
                        <h3>Segurança</h3>
                        <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. 
                           Cum, eum. Incidunt modi velit officiis aut a commodi. 
                           Veritatis, modi ratione quod vitae corporis fugit 
                           laborum numquam illo illum, eveniet provident!
                        </p>
                    </li>
                    <li>    
                        <i class="fas fa-rocket"></i>
                        <h3>Performance</h3>
                        <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. 
                           Cum, eum. Incidunt modi velit officiis aut a commodi. 
                           Veritatis, modi ratione quod vitae corporis fugit 
                           laborum numquam illo illum, eveniet provident!
                        </p>
                    </li>
                    <li>    
                        <i class="fas fa-comments"></i>
                        <h3>Suporte 24/7</h3>
                        <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. 
                           Cum, eum. Incidunt modi velit officiis aut a commodi. 
                           Veritatis, modi ratione quod vitae corporis fugit 
                           laborum numquam illo illum, eveniet provident!
                        </p>
                    </li>
                </ul>    
            </section> 
            <section class="pricing-container">
                <h2>Planos e Preços</h2>
                <p>Selecione o plano que atende as suas necessidades</p>
                <div class="plans-container">
                    <div class="plan">
                        <ul>
                            <li class="price">R$50/mês</li>
                            <li class="plan-name">Básico</li>
                            <li>1 balde de brinde por mês</li>
                            <li>1 Delivery Grátis</li>
                            <li>2 petiscos por entrega</li>
                            <li>2 latas de refrigerantes</li>
                            <li>Suporte 24/7</li>
                            <li class="plan-btn">Saber mais</li>
                        </ul>    
                    </div>
                    <div class="plan">
                        <ul>
                            <li class="price">R$100/mês</li>
                            <li class="plan-name">Dedicado</li>
                            <li>2 balde de brinde por mês</li>
                            <li>3 Delivery Grátis</li>
                            <li>2 petiscos por entrega</li>
                            <li>2 latas de refrigerantes</li>
                            <li>Suporte 24/7</li>
                            <li class="plan-btn">Saber mais</li>
                        </ul>    
                    </div>    
                    <div class="plan">
                        <ul>
                            <li class="price recommended">R$200/mês</li>
                            <li class="plan-name">Dedicado Plus</li>
                            <li>3 balde de brinde por mês</li>
                            <li>5 Delivery Grátis</li>
                            <li>3 petiscos por entrega</li>
                            <li>4 latas de refrigerantes</li>
                            <li>Suporte 24/7</li>
                            <li class="plan-btn recommended">Saber mais</li>
                        </ul>    
                    </div>    
                    <div class="plan">
                        <ul>
                            <li class="price">R$300/mês</li>
                            <li class="plan-name">Flow</li>
                            <li>6 balde de brinde por mês</li>
                            <li>10 Delivery Grátis</li>
                            <li>6 petiscos por entrega</li>
                            <li>10 latas de refrigerantes</li>
                            <li>Suporte 24/7</li>
                            <li class="plan-btn">Saber mais</li>
                        </ul>    
                    </div>        
                </div>
            </section> 
            <section class="searchdomain-container">
                <h2>Quer personalizar seu plano?</h2>
                <p>Verifique planos de acordo com o valor</p>
                <form>
                    <input 
                    type="text" 
                    name="domain" 
                    id="domain" 
                    placeholder="Digite o valor desejado"
                    />
                    <input type="submit" value="Procurar plano">
                </form>
                </div>     
            </section>  
            <section class="contact-container">
                <h2>Mande uma mensagem</h2>  
                <p>Envie a sua mensagem, em até 4 horas um especialista entrará em contato</p>
                <form>
                    <input type="text" name="name" id="name" placeholder="Seu nome">
                    <input type="text" name="email" id="email" placeholder="Seu e-mail">
                    <textarea 
                    name="message" 
                    id="message" 
                    placeholder="Descreva o que você precisa ou o sua necessidade..."
                    ></textarea>
                    <input type="submit" value="Enviar">
                </form>  
            </section>          
        </main>
        <footer>
            <p>&copy; 2025 bNM Drink </p>
    </div>
</body>
</html>
