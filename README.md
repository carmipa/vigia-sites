# vigia-sites

Confere de fora, uma vez por dia (08:17 de São Paulo), os sites carminati.dev.br, carminati.fst.br e finocchio.fst.br:

- cada página do `sitemap.xml` responde 200 (e há pelo menos 5);
- o `robots.txt` aponta o sitemap, e um endereço inexistente responde 404;
- o certificado do domínio e do `www` vale por mais de 20 dias.

Quando algo falha, o GitHub manda e-mail para a conta dona do repositório. Para rodar na hora: aba **Actions**,
fluxo **vigia**, **Run workflow**.

Não usa segredo e não escreve nada. O GitHub desliga o agendamento de repositório sem commit há 60 dias (e avisa por
e-mail antes); um commit qualquer o religa.
