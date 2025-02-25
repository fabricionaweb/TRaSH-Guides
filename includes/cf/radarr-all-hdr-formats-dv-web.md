??? abstract "All HDR Formats + DV (WEBDL) - [Click to show/hide]"

    {! include-markdown "../../includes/cf/dv-info.md" !}

    ![!HDR Formats Flowchart](/Radarr/images/flowchart-hdr-formats.png)

    | Custom Format                                                                                             |                             Score                              | Trash ID                                        |
    | --------------------------------------------------------------------------------------------------------- | :------------------------------------------------------------: | ----------------------------------------------- |
    | [{{ radarr['cf']['dv-hdr10']['name'] }}](/Radarr/Radarr-collection-of-custom-formats/#dv-hdr10)           |   {{ radarr['cf']['dv-hdr10']['trash_scores']['default'] }}    | {{ radarr['cf']['dv-hdr10']['trash_id'] }}      |
    | [{{ radarr['cf']['dv']['name'] }}](/Radarr/Radarr-collection-of-custom-formats/#dv)                       |      {{ radarr['cf']['dv']['trash_scores']['default'] }}       | {{ radarr['cf']['dv']['trash_id'] }}            |
    | [{{ radarr['cf']['dv-hlg']['name'] }}](/Radarr/Radarr-collection-of-custom-formats/#dv-hlg)               |    {{ radarr['cf']['dv-hlg']['trash_scores']['default'] }}     | {{ radarr['cf']['dv-hlg']['trash_id'] }}        |
    | [{{ radarr['cf']['dv-sdr']['name'] }}](/Radarr/Radarr-collection-of-custom-formats/#dv-sdr)               |    {{ radarr['cf']['dv-sdr']['trash_scores']['default'] }}     | {{ radarr['cf']['dv-sdr']['trash_id'] }}        |
    | [{{ radarr['cf']['hdr10plus']['name'] }}](/Radarr/Radarr-collection-of-custom-formats/#hdr10plus)         |   {{ radarr['cf']['hdr10plus']['trash_scores']['default'] }}   | {{ radarr['cf']['hdr10plus']['trash_id'] }}     |
    | [{{ radarr['cf']['hdr10']['name'] }}](/Radarr/Radarr-collection-of-custom-formats/#hdr10)                 |     {{ radarr['cf']['hdr10']['trash_scores']['default'] }}     | {{ radarr['cf']['hdr10']['trash_id'] }}         |
    | [{{ radarr['cf']['hdr']['name'] }}](/Radarr/Radarr-collection-of-custom-formats/#hdr)                     |      {{ radarr['cf']['hdr']['trash_scores']['default'] }}      | {{ radarr['cf']['hdr']['trash_id'] }}           |
    | [{{ radarr['cf']['hdr-undefined']['name'] }}](/Radarr/Radarr-collection-of-custom-formats/#hdr-undefined) | {{ radarr['cf']['hdr-undefined']['trash_scores']['default'] }} | {{ radarr['cf']['hdr-undefined']['trash_id'] }} |
    | [{{ radarr['cf']['pq']['name'] }}](/Radarr/Radarr-collection-of-custom-formats/#pq)                       |      {{ radarr['cf']['pq']['trash_scores']['default'] }}       | {{ radarr['cf']['pq']['trash_id'] }}            |
    | [{{ radarr['cf']['hlg']['name'] }}](/Radarr/Radarr-collection-of-custom-formats/#hlg)                     |      {{ radarr['cf']['hlg']['trash_scores']['default'] }}      | {{ radarr['cf']['hlg']['trash_id'] }}           |
    | [{{ radarr['cf']['dv-webdl']['name'] }}](/Radarr/Radarr-collection-of-custom-formats/#dv-webdl)           |   {{ radarr['cf']['dv-webdl']['trash_scores']['default'] }}    | {{ radarr['cf']['dv-webdl']['trash_id'] }}      |

    !!! tip
        If you (or family members you share your collection with) have a setup that doesn't support Dolby Vision then it's best to add **ALL** the HDR Formats listed above (including **ALL** the DV ones (with and without HDR in it)), It is important to also add the [{{ radarr['cf']['dv-webdl']['name'] }}](/Radarr/Radarr-collection-of-custom-formats/#dv-webdl) Custom Format with a score of {{ radarr['cf']['dv-webdl']['trash_scores']['default'] }}
