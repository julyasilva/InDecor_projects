# InDecor_projects
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>InDecor</title>
    <!-- Text font -->
    <link rel="stylesheet" href="css/styles.css" />
    <!-- <link rel="preconnect" href="https://fonts.googleapis.com&quot; />
    <link rel="preconnect" href="https://fonts.gstatic.com&quot; crossorigin /> -->
    <link
      href="https://fonts.googleapis.com/css2?family=Montserrat:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&display=swap;
      rel="stylesheet"
    />
    <!-- Icons Font -->
    <link
      rel="stylesheet"
      href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.8.1/font/bootstrap-icons.css";
    />
</head>
<body>
    <header id="event-subscription">
        <div id="disclaimer">
            <h2>InDecor</h2>
            <p class="about-event">
                Um evento para revolucionar a sua criatividade 
            </p>
            <p class="event-date">Domingo, 28 de Maio, a partir 14h</p>
        </div>
        <div id="subscription-form">
            <p>Preencha o formulário para receber os detalhes do evento</p>
            <form>
                <div class="form-group">
                    <label for="name">Nome</label>
                    <input type="text" placeholder="Digite seu nome">
                </div>
                <div class="form-group">
                    <label for="email">E-mail</label>
                    <input type="email" placeholder="Digite seu melhror e-mail">
                </div>
                <div class="form-group">
                    <label for="phone">Telefone</label>
                    <input type="text" placeholder="Número de Whatsapp">
                </div>
                <div class="form-group">
                    <label for="interest">Principal interesse</label>
                    <select name="interest">
                        <option value="" disabled selected>Selecione</option>
                        <option value="apartment">Apartamentos</option>
                        <option value="house">Casas</option>
                        <option value="garden">Jardins</option>
                        <option value="other">Outro</option>
                    </select>
                </div>
                <input type="submit" class="btn" value="Quero me increver">
            </form>
        </div>
    </header>
    <section id="key-benefits">
        <h2>O que você vai aprender</h2>
        <div class="benefits">
            <div class="benefit">
                <div id="benefit-1" class="benefit-img"></div>
                <p>
                    Alguma coisa muito legal, que vai fazer a diferença na vida do participante.
                </p>
            </div>
            <div class="benefit">
                <div id="benefit-2" class="benefit-img"></div>
                <p>
                    Alguma coisa muito legal, que vai fazer a diferença na vida do participante.
                </p>
            </div>
            <div class="benefit">
                <div id="benefit-3" class="benefit-img"></div>
                <p>
                    Alguma coisa muito legal, que vai fazer a diferença na vida do participante.
                </p>
            </div>
        </div>
    </section>
    <section id="location">
        <div id="address"></div>
            <i class="bi bi-geo-alt-fill"></i>
                <div id="address-details">
                <p>Rua do evento, 1333</p>
                <p>Bairro</p>
                 <p>Abertura: 14h</p>
             </div>
         </div>
         <div id="about-location">
            <h3>Local de destaque</h3>
            <p>
                O evento será realizado em um local prestigiado pelos amantes de
                Design de Interiores, onde teremos exemplos de vários ambientes, tanto
                intermos como externos.
            </p>
         </div>
    </section>
    <section id="details">
        <div class="detail" id="detail-1">
            <img src="img/hrz-3.jpg" alt="">
            <div class="detail-description">
                <h3>Conheça os ambientes que você vai aprender a decorar</h3>
            </div>
        </div>
        <div class="detail" id="detail-2">
            <div class="detail-description">
                <h3>detalhes</h3>
                <ul>
                    <li>Posicionamento</li>
                    <li>Aproveitamento</li>
                    <li>Combinação de cores</li>
                    <li>Organização</li>
                    <li>E muito mais...</li>
                </ul>
            </div>
            <img src="img/hrz-4.jpg" alt="">
        </div>
        <div class="detail" id="detail-3">
            <img src="img/hrz-5.jpg" alt="">
            <div class="detail-description">
                <h3>Objetos</h3>
                <ul>
                    <li>Caderas</li>
                    <li>Mesas</li>
                    <li>Espelhos</li>
                    <li>Plantas</li>
                    <li>Cortinas</li>
                    <li>E muito mais...</li>
                </ul>
            </div>
        </div>
    </section>
    <section id="cta">
        <h3>Gostou? Então se inscreva:</h3>
        <button class="btn"Solicitar Incrição></button>
    </section>
    <footer id="footer">
        <h3>InDecor</h3>
        <p>A evolução da decoração de inetriores</p>
        <p><span>Entre em contato</span>oi@indecor.com.br</p>
        <p><span>Ou pelo telefone:</span> (55)99990-9999</p>
    </footer>
</body>
</html>
