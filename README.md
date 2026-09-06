# Open Source & Free Tools for Broadcast, OTT Video Streaming, and Ad Insertion

This repository catalogs open-source and free tools for Broadcast and OTT workflows[cite: 1]. It is organized by workflow stages for clarity[cite: 1]. Some tools appear in multiple stages due to their cross-domain usage[cite: 1].

## 1. Broadcast Workflow Stages

### Content Acquisition & Ingest

- **[OBS Studio](https://obsproject.com):** Open-source live streaming software to capture live video/audio feeds[cite: 1]. Supports RTMP, SRT, and other protocols[cite: 1]. Widely used for live events and contribution feeds[cite: 1].
- **[GStreamer Capture](https://gstreamer.freedesktop.org):** Multimedia framework pipelines to capture and process live feeds from SDI/IP capture cards, webcams, and network streams[cite: 1].
- **[SRT (Secure Reliable Transport)](https://www.srtalliance.org):** Open-source protocol for secure, low-latency contribution feeds over public internet[cite: 1]. Handles packet loss, jitter, and encryption[cite: 1].
- **[RIST Protocol](https://www.videorist.org):** Reliable Internet Stream Transport for secure IP contribution[cite: 1]. Provides encryption and error correction[cite: 1].
- **[FFmpeg Capture](https://ffmpeg.org):** Command-line tool to capture feeds from SDI/IP devices or streams[cite: 1]. Supports MPEG-TS, RTP, RTMP, SRT[cite: 1].
- **[NDI Tools](https://ndi.tv/tools):** Network Device Interface protocol for low-latency video transport over LAN/WAN studio-to-studio contribution[cite: 1].
- **[Tvheadend](https://tvheadend.org):** Open-source TV streaming server to capture DVB-S, DVB-C, DVB-T, and ATSC feeds[cite: 1].
- **[VLC Capture](https://www.videolan.org/vlc):** Open-source media player for capturing and streaming contribution feeds via RTSP, RTP, RTMP, and SRT[cite: 1].

### Encoding & Transcoding

- **[FFmpeg Broadcast Encoding](https://ffmpeg.org):** Command-line encoder for real-time MPEG-2, H.264, HEVC encoding[cite: 1]. Supports DVB/ATSC-compliant MPEG-TS output and SCTE-35 markers[cite: 1].
- **[x264](https://www.videolan.org/developers/x264.html):** Open-source H.264 encoder library for high-quality, low-latency broadcast-grade AVC encoding[cite: 1].
- **[x265](https://x265.org):** Open-source HEVC encoder library for UHD/4K channels, supporting HDR workflows[cite: 1].
- **[SVT-HEVC](https://github.com/OpenVisualCloud/SVT-HEVC):** Scalable Video Technology HEVC encoder optimized for multi-core CPUs, enabling real-time UHD broadcast encoding[cite: 1].
- **MPEG-2 Encoding Tools:** Legacy broadcast encoder libraries for DVB/ATSC channels to ensure compliance with legacy set-top boxes (supported in FFmpeg and GStreamer)[cite: 1].
- **[GStreamer Broadcast Pipelines](https://gstreamer.freedesktop.org):** Multimedia framework for real-time broadcast encoding supporting MPEG-2, H.264, and HEVC codecs[cite: 1].

### Multiplexing & Distribution (Standards)

- **[OpenCaster](http://www.opencaster.com):** Open-source DVB multiplexer and distribution tool[cite: 1]. Generates DVB-compliant MPEG-TS streams and supports PSI/SI table generation and SCTE-35 insertion[cite: 1].
- **[FFmpeg TS Muxing](https://ffmpeg.org):** Command-line tool to combine multiple streams into MPEG-TS, adding metadata and SCTE-35 signaling[cite: 1].
- **[DVBlast](https://www.videolan.org/projects/dvblast.html):** Simple DVB streaming application developed by the VideoLAN project supporting DVB-S/S2, DVB-C, DVB-T[cite: 1].
- **[TSDuck](https://tsduck.io):** Transport stream toolkit to analyze, manipulate, and multiplex MPEG-TS, supporting DVB, ATSC, and ISDB standards[cite: 1].
- **[Multicat](https://www.videolan.org/projects/multicat.html):** IP multicast distribution toolkit for distributing multiple MPEG-TS streams over IP networks[cite: 1].
- **[TVHeadend](https://tvheadend.org):** IPTV and DVB streaming server for playout and IP distribution[cite: 1].
- **[MuMuDVB](https://www.mumudvb.net):** DVB to IP streaming tool for multicast/unicast distribution[cite: 1].

### Playout & Automation

- **[CasparCG](https://casparcg.com):** Open-source broadcast graphics and playout server supporting video, audio, and dynamic graphics[cite: 1].
- **[OpenBroadcaster](https://openbroadcaster.com):** Open-source radio/TV automation and scheduling system with web-based scheduling and playlist management[cite: 1].
- **[OCTOPUS Newsroom Alternatives](https://www.octopus-news.com):** Newsroom automation and rundown management concepts that integrate with playout servers like CasparCG[cite: 1].
- **[MythTV](https://www.mythtv.org):** Open-source DVR and automated playout system supporting live TV and scheduled recordings[cite: 1].
- **[LibreTime](https://libretime.org):** Radio automation and playout system with a web-based interface for scheduling playlists[cite: 1].
- **[TV Automation Frameworks (e.g., EBU-TT Live Toolkit)](https://github.com/ebu/ebu-tt-live-toolkit):** Frameworks providing playlist-based playout with metadata-driven automation[cite: 1].
- **[FFmpeg Scheduled Playout](https://ffmpeg.org):** Command-line playout automation supporting MPEG-TS, HLS, and DASH outputs with SCTE-35 cues[cite: 1].
- **[VLC Scheduled Playout](https://www.videolan.org/vlc):** Media player with scheduling capabilities for lightweight playout[cite: 1].

### Monitoring & Compliance

- **[TSDuck Analyzers](https://tsduck.io):** Transport stream analysis toolkit for validation, analyzing PSI/SI tables and SCTE-35 markers[cite: 1].
- **[FFmpeg Probes](https://ffmpeg.org):** Command-line probing utility providing detailed codec, bitrate, and container information[cite: 1].
- **[EBU Loudness Tools](https://tech.ebu.ch/publications/r128):** Loudness measurement utilities measuring LUFS for EBU R128 standards[cite: 1].
- **[ITU Loudness Measurement](https://www.itu.int/rec/R-REC-BS.1770):** Compliance tools measuring integrated loudness and true peak levels for ITU-R BS.1770 standards[cite: 1].
- **[Multicat Monitoring](https://www.videolan.org/projects/multicat.html):** IP multicast monitoring tool for IPTV headend compliance checks[cite: 1].
- **[Wireshark](https://www.wireshark.org):** Network protocol analyzer to monitor IP contribution feeds, supporting RTP, MPEG-TS over IP, SRT, and RTMP[cite: 1].

---

## 2. OTT Workflow Stages

### Live Streaming & Ingest

- **[OBS Studio](https://obsproject.com):** Open-source live streaming software for OTT ingest, supporting RTMP, SRT, and custom streaming outputs[cite: 1].
- **[GStreamer Live Pipelines](https://gstreamer.freedesktop.org):** Multimedia framework pipelines to capture and process live feeds from multiple sources into RTMP, SRT, or MPEG-TS[cite: 1].
- **[SRT (Secure Reliable Transport)](https://www.srtalliance.org):** Open-source transport protocol handling packet loss, jitter, and encryption for secure IP contribution[cite: 1].
- **[RIST Protocol](https://www.videorist.org):** Reliable Internet Stream Transport protocol providing encryption and error correction[cite: 1].
- **[FFmpeg Live Streaming](https://ffmpeg.org):** Command-line tool to ingest and distribute live streams supporting RTMP, SRT, RTP, and HLS/DASH outputs[cite: 1].
- **[Nginx RTMP Module](https://github.com/arut/nginx-rtmp-module):** Nginx module providing RTMP ingest and HLS/DASH output[cite: 1].

### Transcoding & Packaging

- **[Bento4](https://www.bento4.com):** MP4 and DASH/HLS packaging toolkit generating adaptive bitrate ladders and manifests with encryption support[cite: 1].
- **[Shaka Packager](https://github.com/shaka-project/shaka-packager):** Media packaging and encryption tool supporting HLS, DASH, CMAF packaging, and Widevine, PlayReady, and FairPlay DRM[cite: 1].
- **[MP4Box (GPAC)](https://gpac.io):** Multimedia packaging tool for adaptive bitrate packaging into DASH/HLS and CMAF[cite: 1].
- **[FFmpeg Segmenter](https://ffmpeg.org):** Command-line transcoding and packaging tool generating HLS playlists and segments[cite: 1].
- **[Dash.js Reference Packaging](https://dashif.org):** Reference MPEG-DASH packaging tools providing test vectors and reference implementations[cite: 1].

### DRM & Content Protection

- **[Widevine](https://www.widevine.com):** DRM system by Google for OTT content protection on Android/Chrome, supporting modular DRM with encryption and license delivery[cite: 1].
- **[PlayReady](https://www.microsoft.com/playready):** DRM system by Microsoft supporting AES encryption and license servers for Windows and Xbox[cite: 1].
- **[FairPlay](https://developer.apple.com/streaming/fps):** DRM system by Apple supporting HLS with encrypted segments for iOS, macOS, and Apple TV[cite: 1].
- **[Clearkey DRM](https://www.w3.org/TR/encrypted-media/):** Open DRM standard (W3C EME) providing lightweight encryption for OTT testing[cite: 1].
- **[EZDRM Alternatives](https://www.ezdrm.com):** Open-source license server frameworks for DRM delivery and hybrid deployments[cite: 1].
- **[Multi-DRM Frameworks](https://github.com/VideoExpertsGroup/multi-drm):** Orchestration frameworks managing Widevine, PlayReady, and FairPlay via unified APIs[cite: 1].

### CDN & Edge Delivery

- **[Nginx](https://nginx.org):** Web server and reverse proxy supporting HLS/DASH segment caching and edge delivery[cite: 1].
- **[Apache Traffic Server](https://trafficserver.apache.org):** High-performance caching proxy server supporting HTTP/2, TLS, and advanced caching policies[cite: 1].
- **[Varnish Cache](https://varnish-cache.org):** Web application accelerator offering flexible caching rules via VCL for HLS/DASH manifests and segments[cite: 1].
- **[Squid Proxy](http://www.squid-cache.org):** Proxy caching server supporting HTTP/HTTPS caching for OTT testing environments[cite: 1].
- **[OpenCDN / CDNJS](https://github.com/opencdn):** Community-driven CDN frameworks for custom OTT delivery focusing on scalability and cost reduction[cite: 1].
- **[MinIO](https://min.io):** Cloud-native object storage acting as origin storage for OTT/CDN delivery with S3-compatible APIs[cite: 1].
- **[Caddy Server](https://caddyserver.com):** Web server providing secure OTT edge delivery with automatic TLS certificate management[cite: 1].

### Player & Playback SDKs

- **[Shaka Player](https://github.com/shaka-project/shaka-player):** JavaScript player for web browsers supporting DASH, HLS, CMAF, and integrated DRM[cite: 1].
- **[ExoPlayer](https://exoplayer.dev):** Android media player library supporting DASH, HLS, SmoothStreaming, and DRM integration[cite: 1].
- **[Video.js](https://videojs.com):** HTML5 video player framework supporting HLS, DASH via plugins, and Google IMA ads[cite: 1].
- **[HLS.js](https://github.com/video-dev/hls.js):** JavaScript library implementing HLS in browsers via Media Source Extensions (MSE)[cite: 1].
- **[Dash.js](https://github.com/Dash-Industry-Forum/dash.js):** Reference MPEG-DASH player providing test vectors and compliance validation[cite: 1].
- **[Clappr](https://clappr.io):** HTML5 video player supporting HLS, DASH, and progressive MP4, extensible via plugins[cite: 1].

### Advertising & Monetization

- **[Google IMA SDK Integrations](https://developers.google.com/interactive-media-ads):** Client-Side Ad Insertion (CSAI) SDK supporting VAST, VPAID, VMAP[cite: 1].
- **[Open Source SSAI Frameworks](https://github.com/Comcast/scte35-js):** Server-Side Ad Insertion frameworks that dynamically stitch ads into OTT streams to avoid ad blockers[cite: 1].
- **[Video.js Ad Plugins](https://github.com/videojs/videojs-contrib-ads):** Client-side ad insertion plugins integrating with Google IMA SDK[cite: 1].
- **[OpenRTB](https://www.iab.com/guidelines/openrtb):** Real-Time Bidding protocol enabling programmatic ad exchanges and dynamic ad insertion[cite: 1].
- **[Prebid.js](https://prebid.org):** Header bidding framework for OTT web players supporting multiple demand partners[cite: 1].
- **[Ad Server Alternatives (e.g., Revive)](https://www.revive-adserver.com):** Open-source ad server for managing and delivering VAST-compliant ads[cite: 1].

### Analytics & QoE

- **[Streamroot QoE Metrics](https://github.com/streamroot/qoe-metrics):** Open-source QoE monitoring SDK tracking buffering events, bitrate changes, and errors[cite: 1].
- **[YouTube QoE Metrics](https://research.google.com/pubs/archive/43805.pdf):** Playback quality metrics framework providing baseline QoE benchmarks[cite: 1].
- **[Matomo](https://matomo.org):** Open-source, GDPR-compliant web analytics platform tracking user sessions and engagement[cite: 1].

### Recommendation & Personalization

- **[Apache Mahout](https://mahout.apache.org):** Machine learning framework for scalable recommendations, integrating with Hadoop/Spark[cite: 1].
- **[Lens Kit](https://lenskit.org):** Recommender system toolkit providing collaborative filtering and hybrid recommenders[cite: 1].
- **[Surprise](http://surpriselib.com):** Python library for rapid prototyping of recommendation algorithms like SVD and KNN[cite: 1].
- **[RecBole](https://recbole.io):** Unified recommender system framework built on PyTorch supporting over 70 recommendation algorithms[cite: 1].
- **[TensorFlow Recommenders](https://www.tensorflow.org/recommenders):** Deep learning library optimized for production ML pipelines and personalized content discovery[cite: 1].
- **[Implicit](https://github.com/benfred/implicit):** Python library for matrix factorization models optimized for implicit feedback datasets[cite: 1].
- **[PredictionIO](https://predictionio.apache.org):** Machine learning server built on Apache Spark providing REST APIs for recommendations[cite: 1].

### Audience Engagement

- **[Rocket.Chat](https://rocket.chat):** Open-source chat platform supporting live chat, moderation, and API embedding[cite: 1].
- **[Matrix](https://matrix.org):** Decentralized chat protocol providing end-to-end encryption for audience messaging[cite: 1].
- **[StrawPoll](https://strawpoll.com):** Polling and voting tool with a simple API for embedding real-time polls in OTT apps[cite: 1].
- **[Discourse](https://www.discourse.org):** Open-source forum platform supporting threaded discussions and moderation for community engagement[cite: 1].

---

## 3. Shared Tools Across Broadcast & OTT

### Encoding Libraries

- **[FFmpeg](https://ffmpeg.org):** Command-line multimedia toolkit to encode, transcode, and package broadcast/OTT streams[cite: 1].
- **[GStreamer](https://gstreamer.freedesktop.org):** Multimedia framework for real-time encoding and transcoding with a modular pipeline architecture[cite: 1].
- **[libaom](https://aomedia.org):** Official AV1 reference encoder focused on interoperability and compliance[cite: 1].
- **[HandBrake](https://handbrake.fr):** GUI-based open-source transcoder built on FFmpeg and x264/x265 for VOD asset preparation[cite: 1].

### Ad Signaling

- **[SCTE-35](https://www.scte.org/standards/scte-35/):** Digital Program Insertion Cueing Message standard defining splice points for ad insertion[cite: 1].
- **[SCTE-104](https://www.scte.org/standards/scte-104/):** Ad signaling standard for baseband video used in broadcast studios and playout automation[cite: 1].
- **[scte35-js / scte35-python](https://github.com/Comcast/scte35-js):** Open-source parsers and generators for SCTE-35 messages in OTT workflows[cite: 1].

### Subtitles & Accessibility

- **[CCExtractor](https://www.ccextractor.org):** Closed caption extraction tool outputting captions in SRT, WebVTT, and other formats from MPEG-TS and MP4[cite: 1].
- **[Subtitle Edit](https://github.com/SubtitleEdit/subtitleedit):** Subtitle editing software supporting over 200 formats with waveform views for precise syncing[cite: 1].
- **[Aegisub](http://www.aegisub.org):** Advanced subtitle editor supporting ASS/SSA formats with visual timelines and styling[cite: 1].
- **[WebVTT / SRT](https://www.w3.org/TR/webvtt1/):** Subtitle file formats (WebVTT is standardized for web; SRT is simple and universally supported)[cite: 1].
- **[TTML/IMSC](https://www.w3.org/TR/ttml):** XML-based Timed Text Markup Language for rich styling, used in DVB/ATSC/ISDB[cite: 1].

### Metadata & Asset Management

- **[MediaInfo](https://mediaarea.net/en/MediaInfo):** Media metadata inspection tool extracting codec, container, bitrate, and stream-level metadata[cite: 1].
- **[ResourceSpace](https://www.resourcespace.com):** Web-based Digital Asset Management (DAM) system with metadata tagging and search[cite: 1].
- **[CollectiveAccess](https://collectiveaccess.org):** Cataloging and archival system with flexible schema design for custom metadata fields[cite: 1].
- **[DSpace](https://dspace.lyrasis.org):** Digital repository and asset management system supporting standards like Dublin Core[cite: 1].
- **[Fedora Commons](https://duraspace.org/fedora):** Digital repository framework supporting linked data and semantic metadata for compliance-heavy archives[cite: 1].
- **[EBUCore / Dublin Core](https://tech.ebu.ch):** Standardized metadata schemas (EBUCore for interoperability, Dublin Core for descriptive schemas)[cite: 1].

### Storage & Archiving

- **[Ceph](https://ceph.io):** Distributed object, block, and file storage system that is highly fault-tolerant and scalable[cite: 1].
- **[OpenMediaVault](https://www.openmediavault.org):** NAS solution to store assets with a web-based management interface supporting SMB/CIFS, FTP, NFS, and Rsync[cite: 1].
- **[Archivematica](https://www.archivematica.org):** Digital preservation system implementing OAIS-compliant workflows and automating metadata extraction[cite: 1].
- **[iRODS](https://irods.org):** Data management system providing rule-based archival and distributed storage[cite: 1].

### Security & Compliance

- **[Forensic Watermarking](https://github.com/forensic-watermarking):** Content protection libraries embedding invisible watermarks to provide traceability for piracy detection[cite: 1].
- **[Fingerprinting Frameworks](https://github.com/dhowe/AudioFingerprint):** Content identification libraries generating unique fingerprints for unauthorized use detection[cite: 1].
- **[OpenSSL](https://www.openssl.org):** Cryptography and SSL/TLS toolkit providing AES, RSA, and TLS encryption for edge delivery and APIs[cite: 1].

### Data, Analytics & BI

- **[Apache Hadoop](https://hadoop.apache.org):** Distributed storage and processing framework using HDFS and MapReduce[cite: 1].
- **[Apache Spark](https://spark.apache.org):** Unified analytics engine supporting batch and streaming analytics[cite: 1].
- **[Grafana](https://grafana.com) / [Prometheus](https://prometheus.io):** Monitoring toolkits (Prometheus collects time-series metrics; Grafana visualizes QoE/QoS dashboards)[cite: 1].
- **[Elastic Stack (ELK)](https://www.elastic.co/elastic-stack):** Log analysis and visualization suite (Elasticsearch, Logstash, Kibana) for operational logs[cite: 1].
- **[Metabase](https://www.metabase.com) / [Superset](https://superset.apache.org):** BI platforms (Metabase provides simple SQL UI; Superset scales to enterprise visualization)[cite: 1].

### Workflow Orchestration

- **[Apache Airflow](https://airflow.apache.org):** Workflow orchestration platform using DAGs for dependencies, extensible via Python operators[cite: 1].
- **[Argo Workflows](https://argoproj.github.io):** Kubernetes-native workflow engine running workflows as Kubernetes pods[cite: 1].
- **[Jenkins](https://www.jenkins.io):** CI/CD automation server automating build, test, and deploy steps[cite: 1].
- **[Node-RED](https://nodered.org):** Flow-based automation tool with a drag-and-drop interface integrating APIs and cloud services[cite: 1].

### Cloud-Native Infrastructure

- **[Kubernetes](https://kubernetes.io) / [Docker](https://www.docker.com):** Container orchestration and containerization platforms automating deployment and scaling[cite: 1].
- **[Terraform](https://www.terraform.io) / [Helm](https://helm.sh):** Infrastructure-as-Code (Terraform) and Kubernetes package management (Helm) tools[cite: 1].
- **[Ansible](https://www.ansible.com):** Configuration management tool providing agentless automation via YAML playbooks[cite: 1].

### AI/ML Integration

- **[TensorFlow](https://www.tensorflow.org) / [PyTorch](https://pytorch.org):** Deep learning frameworks supporting computer vision and NLP models for metadata enrichment[cite: 1].
- **[MLflow](https://mlflow.org):** ML lifecycle management platform tracking, deploying, and managing ML models for reproducibility[cite: 1].
- **[OpenCV](https://opencv.org):** Computer vision library detecting faces, logos, and objects in streams[cite: 1].

### Multi-Platform Delivery

- **[React Native](https://reactnative.dev) / [Flutter](https://flutter.dev):** Cross-platform mobile frameworks providing single codebases for iOS, Android, and web apps[cite: 1].
- **[Smart TV SDKs (Tizen, Roku, WebOS, tvOS, Android TV)](https://developer.tizen.org):** Development kits providing APIs for video playback and DRM integration on television sets[cite: 1].

### Testing & Simulation

- **[Apache JMeter](https://jmeter.apache.org) / [Locust](https://locust.io):** Load testing tools simulating concurrent users and traffic (Locust supports Python scripting)[cite: 1].
- **[Selenium](https://www.selenium.dev):** Browser automation framework automating UI flows and testing QoE metrics[cite: 1].

### DevOps & CI/CD

- **[GitLab CI/CD](https://docs.gitlab.com/ee/ci) / [GitHub Actions](https://github.com/features/actions):** CI/CD platforms using YAML-based workflows for building and deploying applications[cite: 1].
- **[Spinnaker](https://spinnaker.io) / [Argo CD](https://argo-cd.readthedocs.io):** Continuous delivery and GitOps tools managing multi-cloud deployments and rollbacks[cite: 1].

### Security & Identity

- **[Keycloak](https://www.keycloak.org):** IAM platform supporting SSO, OAuth2, OpenID Connect, and SAML for centralized authentication[cite: 1].
- **[OpenIAM](https://www.openiam.com):** Identity governance platform managing user identities and access policies[cite: 1].
- **[Authentik](https://goauthentik.io) / [Ory Hydra](https://www.ory.sh/hydra):** Lightweight authentication providers securing token-based authentication for APIs[cite: 1].

---

## 4. Contribution Guidelines

Contributions are welcome[cite: 1]. To add new tools, please submit a Pull Request (PR) matching the following format: tool name, link, description, and workflow stage[cite: 1].

## 5. License

This repository is recommended to be licensed under MIT or Apache 2.0 to maintain openness[cite: 1].
