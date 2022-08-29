<script>
    import { onMount } from 'svelte'
    onMount(() => {
        const s = document.createElement('script')
        const tag = document.getElementById('utterances')
        s.setAttribute('repo',"zhuganglie/astroblog")
        s.setAttribute('issue-term',"pathname")
        s.setAttribute('label',"comments")
        s.setAttribute('theme',"preferred-color-scheme")
        s.setAttribute('crossorigin',"anonymous")
        s.src = 'https://utteranc.es/client.js'
        tag.parentNode.insertBefore(s, tag)
    })
    </script>
    
    <div id="utterances" class="mt-6"></div>