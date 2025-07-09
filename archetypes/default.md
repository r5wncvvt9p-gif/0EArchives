+++
date = '{{ .Date | time.Format site.Params.dateFormat }}'
draft = true
title = '{{ replace .File.ContentBaseName "-" " " | title }}'
+++
