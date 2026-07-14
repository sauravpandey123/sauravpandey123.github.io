.latest-news-scroll {
  max-height: 260px;
  overflow-y: auto;
  overflow-x: hidden;
  margin: 1rem 0 1.5rem;
  padding: 0.25rem 1rem 0.25rem 0.25rem;
  border-top: 1px solid #eeeeee;
  border-bottom: 1px solid #eeeeee;
  scrollbar-width: thin;
  scrollbar-color: #aaaaaa #f2f2f2;
}

.latest-news-scroll ul {
  margin-top: 0.75rem;
  margin-bottom: 0.75rem;
}

.latest-news-scroll li {
  margin-bottom: 0.6rem;
  line-height: 1.5;
}

.latest-news-scroll::-webkit-scrollbar {
  width: 7px;
}

.latest-news-scroll::-webkit-scrollbar-track {
  background: #f2f2f2;
  border-radius: 8px;
}

.latest-news-scroll::-webkit-scrollbar-thumb {
  background: #aaaaaa;
  border-radius: 8px;
}

.latest-news-scroll::-webkit-scrollbar-thumb:hover {
  background: #888888;
}