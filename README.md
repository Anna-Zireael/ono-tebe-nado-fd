body {
    margin: 0;}
.header {
    display: inline;
    
}

.menu {
    text-align: left;
    justify-items: baseline;
    
}

.menu a {
    flex: 1; /* Элементы занимают все доступное пространство */
    text-align: center; /* Текст по центру */
    align-items: flex-start;

}

.logo {
    display: block;
    margin-left: auto;
    margin-right: auto;

}
    

.contacts {
    text-align: right;
    display: flex;
    gap: 20px;
    flex-direction: column; 
    align-items: flex-end; 
}

.contacts p {
    margin: 0;
    font-size: 14px;
}

.auction {
    background-color: white;
    display: grid;
    background-image: url('../images/cover.jpg'); 
    background-size: cover;
    background-position: center;
    background-repeat: no-repeat; 
    gap: 10px;
    min-width: 850px;
    min-height: 100vh;
    margin: 0;
    font-family: 'Open Sans', sans-serif;
   
}
.title-text {
    
    font-family: Raleway;
    font-weight: 700;
    font-style: Bold;
    font-size: 150px;
    line-height: 115%;
    letter-spacing: 30%;
    text-transform: uppercase;
    background-color: transparent;
    color: #FFFFFF;
}

.title-text_center {
    
    text-align: center;
}
.title-text_rigth {
    text-align: right;
}


.description {
    font-size: 40px;
    color: white;
    text-align: left;
    line-height: 51px;
}

.bid-button {
   font-size: 20px;
    line-height: 25%;
    text-decoration: none;
    cursor: pointer;
    width: 250px;
    text-align: center;
    background-color: transparent;
    color: white;
    border-color: #ccc;
    ;
    
    
}
.description .bid-button {
    display: flex;
    text-align: center;
    
}
* {
    box-sizing: border-box;
}
.nav-section {
    background-color: transparent;
}


.cards-container {
    display: flex;
    justify-content: space-between;
    align-items: center;
    gap: 20px;
    display: grid;
    grid-template-columns: repeat(3, 200px);
    grid-template-rows: repeat(2, 80px);
     gap: 10px;
    min-width: 850px;
    min-height: 100vh;
    margin: 0;
    font-family: 'Open Sans', sans-serif;
    justify-content:space-between;
    position: relative;
    align-content: center;
}

.card {
    position: relative;
    width: 334px;
    height: 694px;
    background-color: #00000099;
    background-image: none;
    color: white;
    padding: 40px;
    transition: transform 0.3s ease-in-out;
    overflow: hidden;
    
}

.card:nth-child(2) { /* Смещение второй карточки */
    left: 0.5px;
}

.card img {
    width: 100%;
    object-fit: cover;
    border-radius: 10px;
    margin-bottom: 20px;
    background-size: 100% 100%;
    background-position: center;
    
}

.card h2 {
    font-size: 22px;
    font-weight: 700;
    line-height: 120%;
    text-transform: uppercase;
    text-decoration: underline;
    max-width: 254px;
    margin-bottom: 20px;
}

.card p {
    font-size: 20px;
    font-weight: 400;
    line-height: 120%;
    max-width: 254px;
}

.see-more {
    font-size: 20px;
    line-height: 100%;
    letter-spacing: 0%;
    background-color: #000000;
    color: white;
    text-decoration: none;
    text-align: center;
    padding: 10px 0;
}

.see-more:hover,
.card:hover {
    transform: scale(1.05);
}
.main-section {
    padding: 15px;
    background-color: transparent;
    gap: 10px;
    min-width: 850px;
    min-height: 100vh;
    margin: 0;
    font-family: 'Open Sans', sans-serif;
    align-content: center;
    display: grid;
    grid-template-columns:  334px 1fr;
 
}

.logo-column {
    background: #000000;
    width: 200px;
    height: 100%;
    border-radius: 100%;
    display: flex;
    align-items: left;
    justify-self: left;
}

.logo {
    display: flex;
    width: 130px;
    height: 180px;
    border-radius: 25%;
}

.auction-title {
    font-size: 40px;
    font-weight: 700;
    line-height: 100%;
    letter-spacing: 0%;
    text-transform: uppercase;
    display: flex;
    align-items: right;
    justify-self: right;
}

.main-text {
    font-size: 20px;
    line-height: 24px;
    letter-spacing: 0%;
    color: black;
    padding-left: 10px;
    display: flex;
    align-items: right;
    justify-self: right;
}

.additional-text {
    font-size: 20px;
    line-height: 24px;
    letter-spacing: 0%;
    color: black;
    padding-left: 10px;
    display: flex;
    align-items: right;
    justify-self: right;
    
}
.footer-section {
    display: inline;
    top: 2848px;
    width: 1100px;
    height: 180px;

}

.footer-contacts {
    left: 50px;
    width: 265px;
    height: 98px;
    text-align: left;
    display: flex;
    justify-content: center;
    flex-direction: row-reverse;
    align-items: flex-start;
}

.contacts .phone {
    width: 264px;
    height: 24px;
    text-align: left;
    display: flex;
    justify-content: center;
    flex-direction: right;
    align-items: flex-end;
}

.email {

    margin: 0;
    padding: 0;
}

.address {
    font-size: 18px;
    line-height: 24.3px;
    margin: 0;
    padding: 0;
}

.menus {

    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: space-between;
   
}

.menus a {
 
    text-decoration: none;
    font-size: 18px;
    line-height: 100%;
}




.socials {
    display: flex;
    align-items: end;
    justify-content: end;    gap: 48px;
   
}

.socials a {

    background-color: #ffffff;
   
}

.socials img {
    width: 48px;
    height: 48px;
}
