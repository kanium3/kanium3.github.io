<script lang="ts">
import TablerBrandMastodon from "~icons/tabler/brand-mastodon";
import TablerBrandGithub from "~icons/tabler/brand-github";
import TablerBrandBluesky from "~icons/tabler/brand-bluesky";
import TablerBubbleText from "~icons/tabler/bubble-text";
</script>

<main>
    <div class="head">
        <img src="kanium.webp" alt="Icon" />
        <h1>kanium3</h1>
    </div>

    <div class="content">
        <ul>
            <li>
                <TablerBrandGithub />:<a
                    href="https://github.com/kanium3"
                >
                    GitHub</a
                >
            </li>
            <li>
                <TablerBrandMastodon />:<a
                    href="https://otadon.com/@kanium"
                >
                    Mastodon</a
                >
            </li>
            <li>
                <TablerBrandBluesky />:<a
                    href="https://bsky.app/profile/kanium.me"
                >
                    Bluesky</a
                >
            </li>
            <li>
                <TablerBubbleText />:<a
                    href="https://zenn.dev/kaninium"
                >
                    Zenn.dev</a
                >
            </li>
        </ul>
    </div>
</main>

<style lang="scss">
    main {
        display: grid;
        grid-template-rows: 180px 1fr;
        gap: 10px;
    }

    .head img {
        height: 46%;
        width: auto;
        border-radius: 50%;
    }

    ul {
        list-style-type: none;
        font-size: 115%;
        padding-left: 1em;
    }

</style>
