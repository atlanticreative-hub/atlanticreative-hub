import React from "react";
import { Waves, Anchor, Ship } from "lucide-react";

export default function Header() {
  return (
    <header>
      <nav aria-label="Main navigation" className="site-nav">
        <a href="/" className="site-logo">
          <h1 className="site-title">
            Atlantic
            {/* decorative icon — hide from assistive tech */}
            <Waves color="#0077be" size={32} aria-hidden="true" />
          </h1>
        </a>

        {/* icons that are decorative: mark aria-hidden or provide accessible labels when meaningful */}
        <div className="nav-icons" aria-hidden="true">
          <Anchor size={20} />
          <Ship size={20} />
        </div>
      </nav>
    </header>
  );
}
