??? abstract "All HDR Formats - [Click to show/hide]"

    {! include-markdown "../../includes/cf/dv-info.md" !}

    ![!HDR Formats Flowchart](/Radarr/images/flowchart-hdr-formats.png)

    | Custom Format                                                                                             |                             Score                              | Trash ID                                        |
    | --------------------------------------------------------------------------------------------------------- | :------------------------------------------------------------: | ----------------------------------------------- |
    | [{{ sonarr['cf']['dv-hdr10']['name'] }}](/Sonarr/sonarr-collection-of-custom-formats/#dv-hdr10)           |   {{ sonarr['cf']['dv-hdr10']['trash_scores']['default'] }}    | {{ sonarr['cf']['dv-hdr10']['trash_id'] }}      |
    | [{{ sonarr['cf']['dv']['name'] }}](/Sonarr/sonarr-collection-of-custom-formats/#dv)                       |      {{ sonarr['cf']['dv']['trash_scores']['default'] }}       | {{ sonarr['cf']['dv']['trash_id'] }}            |
    | [{{ sonarr['cf']['dv-hlg']['name'] }}](/Sonarr/sonarr-collection-of-custom-formats/#dv-hlg)               |    {{ sonarr['cf']['dv-hlg']['trash_scores']['default'] }}     | {{ sonarr['cf']['dv-hlg']['trash_id'] }}        |
    | [{{ sonarr['cf']['dv-sdr']['name'] }}](/Sonarr/sonarr-collection-of-custom-formats/#dv-sdr)               |    {{ sonarr['cf']['dv-sdr']['trash_scores']['default'] }}     | {{ sonarr['cf']['dv-sdr']['trash_id'] }}        |
    | [{{ sonarr['cf']['hdr10plus']['name'] }}](/Sonarr/sonarr-collection-of-custom-formats/#hdr10plus)         |   {{ sonarr['cf']['hdr10plus']['trash_scores']['default'] }}   | {{ sonarr['cf']['hdr10plus']['trash_id'] }}     |
    | [{{ sonarr['cf']['hdr10']['name'] }}](/Sonarr/sonarr-collection-of-custom-formats/#hdr10)                 |     {{ sonarr['cf']['hdr10']['trash_scores']['default'] }}     | {{ sonarr['cf']['hdr10']['trash_id'] }}         |
    | [{{ sonarr['cf']['hdr']['name'] }}](/Sonarr/sonarr-collection-of-custom-formats/#hdr)                     |      {{ sonarr['cf']['hdr']['trash_scores']['default'] }}      | {{ sonarr['cf']['hdr']['trash_id'] }}           |
    | [{{ sonarr['cf']['hdr-undefined']['name'] }}](/Sonarr/sonarr-collection-of-custom-formats/#hdr-undefined) | {{ sonarr['cf']['hdr-undefined']['trash_scores']['default'] }} | {{ sonarr['cf']['hdr-undefined']['trash_id'] }} |
    | [{{ sonarr['cf']['pq']['name'] }}](/Sonarr/sonarr-collection-of-custom-formats/#pq)                       |      {{ sonarr['cf']['pq']['trash_scores']['default'] }}       | {{ sonarr['cf']['pq']['trash_id'] }}            |
    | [{{ sonarr['cf']['hlg']['name'] }}](/Sonarr/sonarr-collection-of-custom-formats/#hlg)                     |      {{ sonarr['cf']['hlg']['trash_scores']['default'] }}      | {{ sonarr['cf']['hlg']['trash_id'] }}           |

    !!! tip
        If you (or family members you share your collection with) have a setup that doesn't support Dolby Vision then it's best to add **ALL** the HDR Formats listed above (including **ALL** the DV ones (with and without HDR in it)), It is important to also add the [{{ sonarr['cf']['dv-webdl']['name'] }}](/Sonarr/sonarr-collection-of-custom-formats/#dv-webdl) Custom Format with a score of {{ sonarr['cf']['dv-webdl']['trash_scores']['default'] }}
