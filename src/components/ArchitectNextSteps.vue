<template>
    <div class="card">
        <div class="card-container">
            <div id="card-header">
                <h4>Congratulations!</h4>
            </div>
            <div class="card-content">
                <p>You've deployed your app locally. Now what?</p>
                <ul>
                    <li>Check out Hot-reloading</li>
                        <ul>
                            <li>Go to <kbd class="cmp_input">nuxt/src/pages/index.tsx</kbd> in your project folder and open it.</li>
                            <li>Update the subtitle <kbd class="cmp_input">“Favorite Movies”</kbd> to <kbd class="cmp_input">“&lt;Your name&gt;’s Favorite Movies”</kbd></li>
                            <li>The app will automatically apply the new changes on save.</li>
                            <li>For additional information, check out our <a target="_blank" href="https://docs.architect.io/">docs</a>.</li>
                        </ul>
                    <li>Deploy your app to the cloud via Architect</li>
                        <ul>
                            <li>Create an account at <a target="_blank" href="https://cloud.architect.io/signup">architect.io</a></li>
                            <li>Login from the CLI via <kbd class="cmp_input">architect login</kbd></li>
                            <li>Register all your components created from the <kbd class="cmp_input">init</kbd> command by running <kbd class="cmp_input"> architect register</kbd> in both the front-end folder and back-end folder</li>
                            <li>Go to the components page and deploy the app!</li>
                        </ul>
                </ul>
            </div>
        </div>
    </div>
</template>

<script lang="ts">
import { Vue, Component } from 'nuxt-property-decorator';

@Component
export default class ArchitectNextSteps extends Vue {}    
</script>