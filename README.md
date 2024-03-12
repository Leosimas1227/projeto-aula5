# projeto-aula5
<!DOCTYPE html>
<html lang="pt">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>imagens, video, listas e tabelas</title>
</head>
<body>
    <h1>imagens</h1>
    <h2>imagens da internet</h2>
    <img src="https://oeco.org.br/wp-content/uploads/oeco-migration//images/stories/dez2011/cataratas-iguacu-marcos_sa_correa.jpg" alt="paisagem da cataratas do iguaçu" width="500px" height="500px"> 

    <h2>imagens do projeto</h2>
    <img src="imagens/natureza 1.jpg.jpg" alt="texto alternativo" width="500px" height="500px">

    <h1>videos</h1>
    <h2>videos da internet</h2>
    <video controls width="500px" src="https://www.gov.br/pt-br/midias-agorabrasil/video-fundo.mp4/@@download/file"></video>

    <h2>videos do projeto</h2>
    <video src="videos/video-fundo.mp4"></video>

    <h2>videos do youtube</h2>
    <iframe width="800px" height="500px" src="https://www.youtube.com/embed/xMnulm790CQ?si=jsI7z8Ur-YV1J0JB" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

    <h2>videos tiktok</h2>
    <blockquote class="tiktok-embed" cite="https://www.tiktok.com/@anaa_chr2/video/7342311449714380037" data-video-id="7342311449714380037" style="max-width: 605px;min-width: 325px;" > <section> <a target="_blank" title="@anaa_chr2" href="https://www.tiktok.com/@anaa_chr2?refer=embed">@anaa_chr2</a> <p>pronunciamento pra vcs</p> <a target="_blank" title="♬ som original - ana clara 💋" href="https://www.tiktok.com/music/som-original-7342311491189197573?refer=embed">♬ som original - ana clara 💋</a> </section> </blockquote> <script async src="https://www.tiktok.com/embed.js"></script>

    <h1>listas</h1>
    <h2>lista ordenada</h2>
    <ol>
        <li>item numero 1</li>
        <li>item numero 2</li>
    </ol>

    <h2>lista não-ordenada</h2>
    <ul>
<li>café</li>
<li>macarrão</li>
<li>way</li>
<li>feijão</li>
    </ul>

    <h1>tabelas</h1>
    <h2>tabela simples</h2>
    <table border="1">
        <caption>primeira tabela</caption>
        <tr>
            <th>nome</th>
            <th>telefone</th>
        </tr>
        <tr>
            <td>Leonardo</td>
            <td>47 99170 8198</td>
        </tr>
        <tr>
            <td>xpto</td>
            <td>47 99999 9999</td>
        </tr>
    </table>

    <h2>tabela com colspan</h2>
    <table border="1">
        <caption>tabela com colspan</caption>
        <tr>
        <th>nome</th>
        <th colspan="2">telefone</th>
        </tr>
        <tr>
        <td>Leo</td>
        <td>47 99170 8198</td>
        <td>99 99999 9999</td>
        </tr>

    </table>

    <h3>tabela com rowspan</h3>
    <table border="1">
        <caption>tabela com rowspan</caption>
        <tr>
            <th>nome</th>
            <td>Leo</td>
        </tr>
        <tr>
            <th rowspan="2">telefone</th>
            <td>47 99170 8198</td>
        </tr>
        <tr>
            <td>47 99170 8198</td>
        </tr>
    </table>

    <h4>tabela com colspan e rowspan</h4>
    <table border="1">
    <caption>desafio</caption>
    <tr>
        <th>hora</th>
        <th>segunda</th>
        <th>terça</th>
        <th>quarta</th>
    </tr>
    <tr>
        <td>7:30-12:00</td>
        <td colspan="3">trabalhar</td>
    </tr>
    <tr>
        <td rowspan="2">12:00-13:00</td>
        <td>almoço</td>
        <td rowspan="2">almoço</td>
        <td>almoço</td>
    </tr>
    <tr>
        <td>ler</td>
        <td>ler</td>
    </tr>

</table>
</body>
</html>
