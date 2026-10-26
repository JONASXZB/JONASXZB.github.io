# JONASXZB AI Agent Notes

Personal technical notes and tutorials.

- [Getting Started with Beacon Heartbeats for AI Agents](https://jonasxzb.github.io/)
- [RSS feed](https://jonasxzb.github.io/rss.xml)

The tutorial has a keyboard-accessible table of contents and stable section links, such as [`#python-example`](https://jonasxzb.github.io/#python-example). RSS item anchors point to the article itself. Canonical and Open Graph metadata, `robots.txt`, and `sitemap.xml` describe the public site.

## Local preview

No build step or third-party dependencies are required:

```bash
python3 -m http.server 8000 --bind 127.0.0.1
```

Check the page at port 8000, follow the section links with the keyboard, and verify `rss.xml` and `sitemap.xml` are served. Validate both XML documents with:

```bash
python3 -c "import xml.etree.ElementTree as ET; ET.parse('rss.xml'); ET.parse('sitemap.xml')"
```
