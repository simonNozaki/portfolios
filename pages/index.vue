<template>
  <div class="body__text">
    <div class="mt-2">
      <p>
        ソフトウェアエンジニアです。
      </p>
      <p>
        Javaの開発からキャリアをはじめ、バックエンドの開発に従事してきました。
        直近はKotlinの検証および導入や、チームへのドメイン駆動設計の導入を推進してきました。
      </p>
      <p>
        お金を扱うドメインでの経験が長く、運用や監視も含めて堅牢なアーキテクチャの設計が得意です。
      </p>
      <p>
        Intellij IDEAやKotlinなど、JetBrains製品を愛用しています。最近はモダンフロントエンドに入門中。
      </p>
    </div>
    <div>
      <h3 class="body__heading"> Artifacts </h3>
      <p>
        リンクから作ったものに飛べます。
      </p>
      <v-card
        dark
        class="blue-grey darken-4 mt-2"
      >
        <v-simple-table class="blue-grey darken-4 body__text">
          <tbody>
            <tr>
              <td>
                <img
                  src="https://www.vectorlogo.zone/logos/java/java-icon.svg"
                  alt="java"
                  width="20"
                  height="20"
                  class="mr-2"
                />
                Java
              </td>
            </tr>
            <tr>
              <td>
                <img
                  src="https://www.vectorlogo.zone/logos/kotlinlang/kotlinlang-icon.svg"
                  alt="kotlin"
                  width="20"
                  height="20"
                  class="mr-2"
                />
                <a href=""> Kotlin </a>
              </td>
            </tr>
            <tr>
              <td>
                <img
                  src="https://raw.githubusercontent.com/devicons/devicon/master/icons/typescript/typescript-original.svg"
                  alt="typescript"
                  width="20"
                  height="20"
                  class="mr-2"
                />
                TypeScript
              </td>
            </tr>
            <tr>
              <td>
                <img
                  src="https://www.vectorlogo.zone/logos/serverless/serverless-icon.svg"
                  alt="serverless"
                  width="20"
                  height="20"
                  class="mr-2"
                />
                Serverless Framework
              </td>
            </tr>
          </tbody>
        </v-simple-table>
      </v-card>
    </div>
  </div>
</template>

<script>
export default {
  name: 'IndexPage',
}
</script>
