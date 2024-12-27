# Certificados Digitais

## O que são certificados digitais?

- Os certificados digitais são documentos eletrônicos que servem como uma identidade digital para pessoas físicas, jurídicas, ou sistemas. 
- Eles garantem a autenticidade, integridade e validade de informações em meios digitais, funcionando de forma semelhante a um documento oficial em papel.
- Os certificados digitais são amplamente usados em áreas como transações financeiras, emissão de notas fiscais eletrônicas, e autenticação em sistemas governamentais, como o e-CAC no Brasil.
- O certificado digital não é um XML, mas ele pode ser representado ou transportado em formatos baseados em XML dependendo do contexto.
- Um certificado digital é um arquivo eletrônico que segue padrões internacionais, como o X.509

## Principais Elementos de um Certificado Digital

- Nome do Titular
    - pessoa física ou jurídica
- Chave Pública 
    - Um componente usado para criptografar ou verificar informações. 
    - Está associada à identidade do titular.
- Chave Privada 
    - Exclusiva do titular, usada para assinar digitalmente ou descriptografar dados.
- Nome da Autoridade Certificadora (CA) que o emitiu
    - Uma entidade confiável que emite e valida os certificados, assegurando que eles são autênticos.
- Assinatura Digital da CA 
    - Uma garantia de que o certificado foi emitido pela autoridade certificadora correspondente.
- O número de série
- O período de validade    

## Características Importantes

- Autenticação
    - Confirma a identidade de quem está acessando ou enviando informações.
- Criptografia
    - Garante que os dados transmitidos sejam protegidos contra acessos não autorizados.
- Assinatura Digital
    - Assegura que o conteúdo não foi alterado após ser assinado.

## Exemplo Prático

- Imagine que você deseja assinar um contrato online
    - Seu certificado digital é usado para comprovar sua identidade.
    - A assinatura digital vinculada ao certificado garante que o contrato não foi alterado após a assinatura.
    - A outra parte pode verificar a autenticidade do documento por meio da autoridade certificadora.

## Principais Formatos de Certificados Digitais

- DER (Distinguished Encoding Rules):
    - Binário.
    - Usado em sistemas que precisam de arquivos compactos.
    - Extensão: .cer ou .der.
- PEM (Privacy Enhanced Mail):
    - Texto base64 com cabeçalhos como -----BEGIN CERTIFICATE-----.
    - Fácil de transportar em texto puro.
    - Extensão: .pem.
- PFX ou PKCS#12:
    - Formato binário que armazena tanto a chave pública quanto a chave privada.
    - Protegido por senha.
    - Extensão: .pfx ou .p12.
- P7B ou PKCS#7:
    - Formato usado para armazenar a cadeia de certificados (não inclui a chave privada).
    - Extensão: .p7b.

## XML

- Certificados digitais podem ser incorporados em arquivos XML dependendo do protocolo ou aplicação. Alguns exemplos:
    - XMLDSig (XML Digital Signature): Um padrão para assinar digitalmente documentos XML. Nesse caso, o certificado digital é usado para criar e verificar a assinatura.
    - e-CNPJ e e-CPF: Em sistemas governamentais, o certificado pode ser utilizado para assinar arquivos XML, como notas fiscais eletrônicas (NF-e), mas o próprio certificado continua no formato X.509.
- O certificado digital em si não é um XML, mas pode ser usado para:
    - Assinar arquivos XML.
    - Ser representado ou referenciado dentro de um XML em aplicações específicas.
    - Se você precisar trabalhar com certificados digitais em XML, é provável que esteja lidando com uma aplicação que encapsula o certificado (como XMLDSig) ou utiliza sua chave pública para assinar/verificar documentos.

## História e evolução no Brasil

- A história dos certificados digitais no Brasil começa com a necessidade de criar um sistema confiável para garantir a segurança e a autenticidade das transações digitais. 
- A implementação desse sistema foi possível graças à criação da Infraestrutura de Chaves Públicas Brasileira (ICP-Brasil).

- 1. Criação da ICP-Brasil (2001):
    - A ICP-Brasil foi estabelecida pela Medida Provisória nº 2.200-2, de 24 de agosto de 2001.
    - Objetivo: Garantir a autenticidade, integridade e validade jurídica de documentos digitais por meio de assinaturas digitais.
    - A ICP-Brasil é composta por uma hierarquia de confiança:
        - ITI (Instituto Nacional de Tecnologia da Informação): Autoridade máxima da cadeia.
    - Autoridades Certificadoras (ACs): Responsáveis por emitir os certificados digitais.
    - Autoridades de Registro (ARs): Fazem a validação presencial dos dados de quem solicita um certificado.
- 2. Expansão e Adoção Inicial:
    - Nos primeiros anos, os certificados digitais foram utilizados principalmente para fins corporativos, como:
        - Envio de notas fiscais eletrônicas (NF-e).
        - Integração com o Sistema Público de Escrituração Digital (SPED).
    - Grandes empresas começaram a adotar certificados para garantir segurança em transações financeiras e autenticação de documentos.
- 3. Popularização:
    - Com o avanço da digitalização, o uso de certificados se expandiu para pessoas físicas e pequenas empresas, principalmente para:
        - e-CPF e e-CNPJ: Ferramentas para autenticação no portal da Receita Federal e envio de declarações.
        - e-Social: Integração de obrigações trabalhistas e previdenciárias.
    - A emissão de certificados em formatos mais acessíveis, como os certificados em nuvem, facilitou a adoção.
- 4. Inovações Recentes:
    - O desenvolvimento de soluções como certificados digitais em dispositivos móveis e integração com aplicativos de assinatura eletrônica trouxe ainda mais praticidade.
    - A adoção cresceu com a obrigatoriedade de sistemas digitais em setores governamentais e empresariais, como no Portal Gov.br.
- Impacto e Relevância:
    - A evolução dos certificados digitais no Brasil consolidou a ICP-Brasil como referência em segurança digital, permitindo maior confiabilidade nas transações eletrônicas e fortalecendo o uso de tecnologias digitais no setor público e privado. 
    - Hoje, o Brasil é um dos países com maior adoção de certificados digitais em diversas áreas da economia.

## Infraestrutura de Chaves Públicas Brasileira (ICP-Brasil)

## Benefícios e aplicações dos certificados digitais

## e-CPF, e-CNPJ e e-Social