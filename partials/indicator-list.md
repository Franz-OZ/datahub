```sql indicators

SELECT id, Name FROM datahubGsheets.source_one_Indicators ORDER BY Name;

```
 
 {#each indicators as indicator}
    <a class="type-Indicator {indicator.id}" href="/indicator/{indicator.id}"><small><code>{indicator.id}</code></small> {indicator.Name}</a> <br>   
 {/each}