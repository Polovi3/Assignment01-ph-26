 # Ai helping section buildig div starting form here 
           <!-- section header div -->

        <section class="schedule-section">
          <div class="schedule-container">
          
            <div class="schedule-header">
              <span class="schedule-badge">Event Agenda</span>
              <h2>Explore the Schedule</h2>
              <p>
                Plan your day around our expert-led tracks, keynote speeches,
                and hands-on developer workshops.
              </p>
            </div>

            <!-- Main container -->
            <div class="timeline">
              <!--season 1 -->
              <div class="timeline-item">
                <div class="timeline-time">
                  <h4>09:00 AM</h4>
                  <p>Duration: 60 mins</p>
                </div>
                <div class="timeline-dot"></div>
                <div class="timeline-content">
                  <span class="tech-tag tag-keynote">Keynote</span>
                  <h3>Opening Ceremony & Tech Vision 2026</h3>
                  <p>
                    Kickstart DevConf 2026 with an overview of the shifting
                    landscape in open-source software, computing paradigms, and
                    decentralized web architectures.
                  </p>
                  <div class="speaker-meta">
                    By <strong>Demis Hassabis</strong> & Team
                  </div>
                </div>
              </div>

              <!-- season 2-->
              <div class="timeline-item highlighted-session">
                <div class="timeline-time">
                  <h4>10:30 AM</h4>
                  <p>Duration: 45 mins</p>
                </div>
                <div class="timeline-dot"></div>
                <div class="timeline-content">
                  <span class="tech-tag tag-ai">AI / ML Track</span>
                  <h3>Scaling LLMs in Production Workflows</h3>
                  <p>
                    An in-depth technical deep dive into optimizing inference
                    costs, context windows, and real-time retrieval-augmented
                    generation (RAG) at scale.
                  </p>
                  <div class="speaker-meta">
                    By <strong>Andrej Karpathy</strong>
                  </div>
                </div>
              </div>

              <!-- season 3 -->
              <div class="timeline-item">
                <div class="timeline-time">
                  <h4>11:30 AM</h4>
                  <p>Duration: 45 mins</p>
                </div>
                <div class="timeline-dot"></div>
                <div class="timeline-content">
                  <span class="tech-tag tag-frontend">Frontend Track</span>
                  <h3>The Future of Rendering Architecture</h3>
                  <p>
                    Exploring server components, partial hydration, and how
                    modern framework compilers are changing client-side
                    performance benchmarks.
                  </p>
                  <div class="speaker-meta">
                    By <strong>Gary Marcus</strong>
                  </div>
                </div>
              </div>

              <!-- season 4 -->
              <div class="timeline-item">
                <div class="timeline-time">
                  <h4>01:00 PM</h4>
                  <p>Duration: 90 mins</p>
                </div>
                <div class="timeline-dot"></div>
                <div class="timeline-content">
                  <span class="tech-tag tag-break">Networking</span>
                  <h3>Lunch Break & Tech Expo Arena</h3>
                  <p>
                    Connect with sponsors, participate in interactive booths,
                    view project demos, and network with 4,000+ fellow
                    engineers.
                  </p>
                </div>
              </div>
            </div>
          </div>
        </section>

        <!-- Ai section div are end here -->
         
# AI Missing link section started for css part 

.schedule-section {
  padding: 100px 20px;
  background-color: #ffffff; 
  font-family: 'Segoe UI', Roboto, Helvetica, Arial, sans-serif;
}

.schedule-container {
  max-width: 1200px;
  margin: 0 auto; 
}


.schedule-header {
  text-align: center;
  max-width: 600px;
  margin: 0 auto 60px auto;
}

.schedule-badge {
  background-color: #eff6ff;
  color: #2563eb;
  padding: 6px 16px;
  font-size: 0.85rem;
  font-weight: 700;
  border-radius: 50px;
  text-transform: uppercase;
  display: inline-block;
  margin-bottom: 15px;
}

.schedule-header h2 {
  font-size: 2.5rem;
  font-weight: 800;
  color: #0f172a;
  margin-bottom: 15px;
}

.schedule-header p {
  color: #64748b;
  font-size: 1.05rem;
  line-height: 1.6;
}


.timeline {
  position: relative;
  max-width: 900px;
  margin: 0 auto;
  padding: 20px 0;
}


.timeline::before {
  content: '';
  position: absolute;
  left: 180px;
  top: 0;
  width: 2px;
  height: 100%;
  background-color: #e2e8f0;
}


.timeline-item {
  display: flex;
  margin-bottom: 40px;
  position: relative;
}


.timeline-time {
  width: 150px;
  text-align: right;
  padding-right: 30px;
  flex-shrink: 0;
}

.timeline-time h4 {
  font-size: 1.15rem;
  font-weight: 700;
  color: #0f172a;
}

.timeline-time p {
  font-size: 0.85rem;
  color: #94a3b8;
  margin-top: 4px;
}

.timeline-dot {
  position: absolute;
  left: 176px;
  top: 4px;
  width: 10px;
  height: 10px;
  border-radius: 50%;
  background-color: #cbd5e1;
  border: 2px solid #ffffff;
  z-index: 2;
  transition: all 0.3s ease;
}

.timeline-content {
  padding-left: 40px;
  flex-grow: 1;
}

.timeline-content h3 {
  font-size: 1.35rem;
  font-weight: 700;
  color: #1e293b;
  margin: 8px 0;
  transition: color 0.3s ease;
}

.timeline-content p {
  color: #475569;
  font-size: 0.95rem;
  line-height: 1.6;
  margin-bottom: 12px;
}

.speaker-meta {
  font-size: 0.9rem;
  color: #64748b;
}

.tech-tag {
  display: inline-block;
  padding: 4px 12px;
  font-size: 0.75rem;
  font-weight: 700;
  border-radius: 6px;
  text-transform: uppercase;
}

.tag-keynote { background-color: #faf5ff; color: #a855f7; }
.tag-ai { background-color: #f0fdf4; color: #16a34a; }
.tag-frontend { background-color: #eff6ff; color: #2563eb; }
.tag-break { background-color: #fff7ed; color: #ea580c; }

.timeline-item:hover .timeline-dot {
  background-color: #2563eb;
  transform: scale(1.3);
}

.timeline-item:hover .timeline-content h3 {
  color: #2563eb;
}

.highlighted-session .timeline-dot {
  background-color: #2563eb;
  width: 14px;
  height: 14px;
  left: 174px;
}

.highlighted-session .timeline-content {
  background-color: #f8fafc;
  padding: 20px 25px 20px 40px;
  border-radius: 12px;
  border-left: 4px solid #2563eb;
}

@media (max-width: 768px) {
  .timeline::before {
    left: 15px;
  }
  
  .timeline-item {
    flex-direction: column;
    padding-left: 35px;
  }
  
  .timeline-time {
    width: 100%;
    text-align: left;
    padding-right: 0;
    margin-bottom: 10px;
  }
  
  .timeline-dot {
    left: 11px;
    top: 5px;
  }
  
  .highlighted-session .timeline-dot {
    left: 9px;
  }
  
  .timeline-content {
    padding-left: 0;
  }
}