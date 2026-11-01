<script lang="ts">
    import notices from "#lib/data/notices.json";
</script>
<h1>ふぁーむふじさき</h1>

<h2>おしらせ</h2>

{#each notices as notice (notice.id)}
    <article>
        <p>{notice.date}</p>
        <h2>{notice.title}</h2>
        <p>{notice.content}</p>
    </article>
{/each}


<a href="./berry/"><p>イチゴのご案内</p></a>
<a href="./pear/"><p>梨のご案内</p></a>
<a href="./access/"><p>アクセス情報</p></a>